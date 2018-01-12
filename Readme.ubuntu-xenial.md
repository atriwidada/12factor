sudo apt install ruby-bundler ruby-dev
sudo gem install bundler
sudo gem install eventmachine -v '1.2.0.1'
bundle install
sudo apt-add-repository 'deb http://toolbelt.herokuapp.com/ubuntu ./'
curl https://toolbelt.herokuapp.com/apt/release.key | sudo apt-key add -
sudo apt update
sudo apt install heroku-toolbelt
heroku local:start
