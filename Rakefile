require 'rubygems'
require 'parallel_tests'
require 'parallel_tests/tasks'

=begin
$ rake -T parallel
rake parallel:create[count]                            # create test databases via db:create --> parallel:create[num_cpus]
rake parallel:drop[count]                              # drop test databases via db:drop --> parallel:drop[num_cpus]
rake parallel:features[count,pattern,options]          # run features in parallel with parallel:features[num_cpus]
rake parallel:features-spinach[count,pattern,options]  # run features-spinach in parallel with parallel:features-spinach[num_cpus]
rake parallel:load_schema[count]                       # load dumped schema for test databases via db:schema:load --> parallel:load_s...
rake parallel:load_structure[count]                    # load structure for test databases via db:structure:load --> parallel:load_st...
rake parallel:migrate[count]                           # update test databases via db:migrate --> parallel:migrate[num_cpus]
rake parallel:prepare[count]                           # update test databases by dumping and loading --> parallel:prepare[num_cpus]
rake parallel:rake[command]                            # launch given rake command in parallel
rake parallel:seed[count]                              # load the seed data from db/seeds.rb via db:seed --> parallel:seed[num_cpus]
rake parallel:spec[count,pattern,options]              # run spec in parallel with parallel:spec[num_cpus]
rake parallel:test[count,pattern,options]              # run test in parallel with parallel:test[num_cpus]
=end