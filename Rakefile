directory "lib"

file "wmls-1.0.0.gem"  => ["wmls.gemspec", "lib/wmls.rb", "bin/wmls"] do
  sh "gem build wmls.gemspec"
end

task :default => "wmls-1.0.0.gem"

