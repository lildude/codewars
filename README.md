# Codewars

My solutions for Codewars problems as I learn Ruby.

This repo includes a little shell script for grabbing a kata, its description and any test data so I can run it locally.

It also includes a slightly modified version of the Codewars [ruby test framework](https://github.com/Codewars/kata-test-framework-ruby/) - it's been modified to be a little friendlier when run on the command line.

# Usage

Grab a random ruby kata:

```console
$ bin/train
```

Grab a specific kata by ID (from the URL):

```console
$ bin/train <id>
```

# Testing

If the kata includes test data, it'll be added to a test file along with `require_relative` statements that pull in the test framework and the `solution.rb`.  

Testing is then as simple as running:

```console
$ ruby katas/<#>kyu/<kata_name>/test.rb
```

# Submitting Your Solution

There isn't any automatic solution submission in this repo yet so until then, you'll need to manually paste and submit it via the web interface.
