forge "http://forge.puppetlabs.com"

# Modules from the Puppet Forge
mod "puppetlabs/apache"
mod "puppetlabs/ntp"
mod 'puppetlabs/firewall'
mod 'puppetlabs/concat', :latest
mod 'puppetlabs/stdlib', :latest
mod 'puppetlabs/inifile', :latest
mod 'nanliu/staging', :latest
mod 'saz/rsyslog', '4.0.2'

mod 'aboe/chrony',
  :git    => 'https://github.com/aboe76/puppet-chrony.git'

mod 'snmp',
# Currently, razersedge/snmp module makes many nosy warnings
# such as Warning: Unknown variable: '::snmp_agentaddress'.
# at /etc/puppetlabs/code/environments/dev/modules/snmp/manifests/params.pp:19:19
# It's not fully support Puppet 4.0 syntax. that's why I used another git repo.
# The origin is :
  #:git   => 'https://github.com/razorsedge/puppet-snmp.git'
  :git    => 'https://github.com/mterzo/puppet-snmp.git',
  :branch => 'enable_strict'
 	#:tag		=> '3.6.0'

mod 'profiles',
  :git 	  => 'https://github.com/netman2k/puppet-profiles.git',
  :branch => 'dev'

mod 'roles',
  :git => 'https://github.com/netman2k/puppet-roles.git'
