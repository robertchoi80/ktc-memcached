#
# vim: set ft=ruby:
#
site :opscode

metadata

cookbook 'ktc-etcd', github: 'cloudware-cookbooks/ktc-etcd', branch: 'develop'
cookbook 'ktc-utils', github: 'cloudware-cookbooks/ktc-utils', branch: 'develop'
cookbook 'openstack-block-storage', github: 'stackforge/cookbook-openstack-block-storage'
cookbook "openstack-common", github: "stackforge/cookbook-openstack-common"
cookbook "openstack-identity", github: "stackforge/cookbook-openstack-identity"
cookbook "openstack-image", github: "stackforge/cookbook-openstack-image"
cookbook 'openstack-object-storage', github: 'stackforge/cookbook-openstack-object-storage'
cookbook 'services', github: 'spheromak/services-cookbook'
cookbook 'yum', github: 'spheromak/yum', branch: 'integration'

group :integration do
  cookbook 'ktc-testing', github: 'cloudware-cookbooks/ktc-testing', branch: 'master'
  cookbook 'ubuntu'
end
