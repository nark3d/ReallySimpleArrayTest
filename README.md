# Really Simple Array Test

A simple array test for PHP developers. There are numerous ways to complete the tasks involved in this test and there are no right, or perfect, answers. The test though will reveal roughly how knowledgeable and experienced a developer is.

## The Test

This test aims to see how well a developer understands arrays and array manipulation.

It is based around a small assocaitive array of users. Each task aims to test a different means of manipulating an array.

### The User Array  

```php
[
    [
        'forename' => 'John',
        'surname' => 'Galt',
        'username' => 'jGalt95',
        'email' => 'j.galt@gmail.com',
        'age' => 22,
        'country' => 'USA',
        'city' => 'New York',
        'created_at' => '2016/04/02 16:53:22'
    ],
    [
        'forename' => 'Anne',
        'surname' => 'Jones',
        'username' => 'AnneJn',
        'email' => 'anne.jones@hotmail.com',
        'age' => 34,
        'country' => 'UK',
        'city' => 'Manchester',
        'created_at' => '2014/09/13 22:02:31'
    ],
    [
        'forename' => 'Craig',
        'surname' => 'Rodriguez',
        'username' => 'Rod4567',
        'email' => 'rod4567@yahoo.com',
        'age' => 19,
        'country' => 'USA',
        'city' => 'Houston',
        'created_at' => '2017/01/29 06:12:59'
    ],
    [
        'forename' => 'Gary',
        'surname' => 'Smith',
        'username' => 'smithy12',
        'email' => 'g.smithy12@gmail.com',
        'age' => 60,
        'country' => 'UK',
        'city' => 'London',
        'created_at' => '2013/11/07 12:11:47'
    ],
    [
        'forename' => 'Stephanie',
        'surname' => 'Lehman',
        'username' => 'stephL89',
        'email' => 'j.galt@gmail.com',
        'age' => 28,
        'country' => 'Germany',
        'city' => 'Munich',
        'created_at' => '2014/04/23 18:12:03'
    ]
];
```

### Task One

Create a new array that only includes users under the age of 30.

The new array should look like this...

```php
[
    [
        'forename' => 'John',
        'surname' => 'Galt',
        'username' => 'jGalt95',
        'email' => 'j.galt@gmail.com',
        'age' => 22,
        'country' => 'USA',
        'city' => 'New York',
        'created_at' => '2016/04/02 16:53:22'
    ],
    [
        'forename' => 'Craig',
        'surname' => 'Rodriguez',
        'username' => 'Rod4567',
        'email' => 'rod4567@yahoo.com',
        'age' => 19,
        'country' => 'USA',
        'city' => 'Houston',
        'created_at' => '2017/01/29 06:12:59'
    ],
    [
        'forename' => 'Stephanie',
        'surname' => 'Lehman',
        'username' => 'stephL89',
        'email' => 'j.galt@gmail.com',
        'age' => 28,
        'country' => 'Germany',
        'city' => 'Munich',
        'created_at' => '2014/04/23 18:12:03'
    ]
];
```

### Task Two

Create a new array that adds a new field called fullname to each array item. This field should combine the values of the forename and surname fields.

Each array item in the new array should have the following output...

```php
[
    'forename' => 'Stephanie',
    'surname' => 'Lehman',
    'username' => 'stephL89',
    'email' => 'j.galt@gmail.com',
    'age' => 28,
    'country' => 'Germany',
    'city' => 'Munich',
    'created_at' => '2014/04/23 18:12:03',
    'fullname' => 'Stephanie Lehman'
]
```

### Task Three

Create a new array where each array item has had the email field removed.

Each array item in the new array should have the following output...

```php
[
    'forename' => 'Stephanie',
    'surname' => 'Lehman',
    'username' => 'stephL89',
    'age' => 28,
    'country' => 'Germany',
    'city' => 'Munich',
    'created_at' => '2014/04/23 18:12:03'
]
```

## Submitting Answers

To submit answers to this test please clone this repo, create a new branch and push it back up once you have completed the tasks.

## Author

Rob Waller: @robdwaller

## License

MIT