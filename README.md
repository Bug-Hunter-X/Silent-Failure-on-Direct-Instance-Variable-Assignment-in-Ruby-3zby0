# Silent Failure on Direct Instance Variable Assignment in Ruby

This repository demonstrates a common, yet subtle, bug in Ruby: the silent failure that occurs when attempting to modify an instance variable directly without a setter method.  In Ruby, instance variables (@value) are generally accessed through getter and setter methods.  Attempting to modify them directly outside of these methods may not raise errors but lead to unexpected behavior.

The `bug.rb` file showcases this issue. The `bugSolution.rb` file provides a corrected version.