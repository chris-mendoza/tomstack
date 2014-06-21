source "https://api.berkshelf.com"

cookbook 'platformstack', git: 'git@github.com:AutomationSupport/platformstack.git'
cookbook 'logstash_stack', git: 'git@github.com:rackspace-cookbooks/logstash_stack.git'
cookbook 'rackspace_iptables', git: 'git@github.com:rackspace-cookbooks/rackspace_iptables.git'
cookbook 'rackspacecloud', git: 'git@github.com:rackspace-cookbooks/rackspacecloud.git'
cookbook 'rackspace_cloudbackup', git: 'git@github.com:rackspace-cookbooks/rackspace_cloudbackup.git'
cookbook 'rackops_rolebook', git: 'git@github.com:rackops/rackops_rolebook.git'
cookbook 'tomcat', git: 'https://github.com/opscode-cookbooks/tomcat.git', tag: 'v0.15.12'
cookbook 'cron', git: 'git@github.com:rackspace-cookbooks/cron.git'
cookbook 'mysql-multi', git: 'git@github.com:rackspace-cookbooks/mysql-multi.git'

group :integration do
  cookbook 'tomstack_test_elasticsearch', path: 'test/fixtures/cookbooks/tomstack_test_elasticsearch'
  cookbook 'tomstack_test_gluster', path: 'test/fixtures/cookbooks/tomstack_test_gluster'
  cookbook 'tomstack_test_app', path: 'test/fixtures/cookbooks/tomstack_test_app'

  cookbook 'apt'
  cookbook 'yum'

  cookbook 'rackspace_gluster', git: 'git@github.com:rackspace-cookbooks/rackspace_gluster.git'
end

metadata
