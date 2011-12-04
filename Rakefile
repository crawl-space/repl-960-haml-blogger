task :compile do
  sh("compass compile")
  sh("haml template.haml template.part")
  sh("premailer template.part > template.html")
end

task :default => :compile
