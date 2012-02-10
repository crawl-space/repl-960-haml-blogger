task :compile do
  sh("compass compile")
  sh("haml template.haml template.part")
#  sh("premailer template.part > template.html")
  sh("cat stylesheets/* > style.css")
  sh("sed -e \"/%%CSS_HERE%%/r style.css\" -e \"/%%CSS_HERE%%/d\" template.part > template.html")
end

task :default => :compile
