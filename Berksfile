source 'https://supermarket.chef.io'

metadata

cookbook 'apt', '~> 6.0.1'

group :integration do
  cookbook 'elasticsearch_test', path: './test/fixtures/cookbooks/elasticsearch_test'

  # not a strict dependency, but necessary for TK testing
  cookbook 'java'
  cookbook 'curl'
end
