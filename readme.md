```ruby
$ rake parallel:test
Command: /.rvm/gems/ruby-2.0.0-p247/gems/parallel_tests-0.16.5/lib/parallel_tests/../../bin/parallel_test test --type test -n  --pattern '' --test-options ''
Looking in ["test"]
Files ["test/false.rb", "test/true.rb"]
Filtered: ["test/false.rb", "test/true.rb"]
4 processes for 2 tests, ~ 0 tests per process
Running cmd: ruby -Itest -e '["/mini_parallel_selenium/test/true.rb"].each {|f| require f }' -- 
Running cmd: ruby -Itest -e '["/mini_parallel_selenium/test/false.rb"].each {|f| require f }' -- 
test | 1 |mini_parallel_selenium/test/false.rb:7
test | 1 |mini_parallel_selenium/test/true.rb:7


Finished in 0s

1 runs, 1 assertions, 0 failures, 0 errors, 0 skips


Finished in 0s

  1) Failure:
test#test_0001_test [/mini_parallel_selenium/test/false.rb:8]:
Expected: 2
  Actual: 1

1 runs, 1 assertions, 1 failures, 0 errors, 0 skips

2 assertions, 0 errors, 1 failure, 2 runs, 0 skips

Took 0.161643 seconds
Tests Failed
```
