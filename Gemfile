source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.3'
gem 'oj'
gem 'benchmark-ips'
gem 'ruby-prof'
gem 'yajl-ruby', require: 'yajl'
