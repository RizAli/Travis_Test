# Travis_Test
Testing how to setup Travis


Step 1 Added yml file

language: ruby
rvm:
  - "1.8.7"
  - "1.9.2"
  - "1.9.3"
  - jruby-18mode # JRuby in 1.8 mode
  - jruby-19mode # JRuby in 1.9 mode
  - rbx
uncomment this line if your project needs to run something other than `rake`:
script: bundle exec rspec spec


Step 2
On github using webhook turned the repository on 


