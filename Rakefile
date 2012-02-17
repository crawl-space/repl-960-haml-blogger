task :compile do
  sh("compass compile")
  sh("haml template.haml template.part")
  sh("cat stylesheets/* > style.css")
  sh("sed -e \"/%%CSS_HERE%%/r style.css\" -e \"/%%CSS_HERE%%/d\" template.part > template.html")
  sh("rm template.part")
  sh("rm style.css")
end

task :default => :compile
