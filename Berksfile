source 'https://api.berkshelf.com'

cookbook 'apt'

group :integration do
  cookbook 'minitest-handler', :git => 'git://github.com/btm/minitest-handler-cookbook.git'
  cookbook 'yum-epel'
  cookbook 'haproxy_test', :path => './test/cookbooks/haproxy_test'
end

metadata
