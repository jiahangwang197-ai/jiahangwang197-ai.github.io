source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

# Windows 和 JRuby 不包含 zoneinfo 文件，使用时需包含此 gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 文件监视性能提升
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# HTTP 服务器
gem "webrick", "~> 1.8"
