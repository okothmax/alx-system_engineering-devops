# update the pc

exec { 'sudo apt-get update':
  path => '~/'
}

# install nginx

package {'sudo apt install -y nginx':
    
}

# Create a directory

file { 'index.html':
  ensure  => 'present',
  content => 'Hello World!',
  mode    => '0744',
  path    => '/var/www/html/index.html',
}
