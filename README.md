Pretty S3 index.html
====================

Authors
-------
Francesco Pasqualini  
Nolan Lawson (http://nolanlawson.com)  
Olivier Scherler (http://olivier.ithink.ch/)  

License
-------
GPL v3

Summary
-------

A Bootstrap-y, pretty index.html designed to be placed at the root of a public Amazon S3 bucket, which
you just want to use for displaying a list of files.

Usage
-----

Just place the index.html file in the root of your bucket.  It'll look [like this][1].

For comparison, the [original index.html created by Amazon][2] looks [like this][3].

Changes
-------

### Francesco Pasqualini

[Original version][2].

### Nolan Lawson

- AJAX request and processing using jQuery;
- Rendering using Handlebars;
- Styling using Bootstrap 2;
- User friendly size and date display;
- Remove column sorting.

### Olivier Scherler

- Support for buckets with more that 1000 (`max-keys`) items;
- Bootstrap 3;
- Opening and closing folders;
- Sort items naturally, ignoring accents;
- Item count on folders;
- Friendlier date format.

[1]: https://nolanlawson.s3.amazonaws.com/index.html
[2]: https://aws.amazon.com/code/1713
[3]: http://regexp.s3.amazonaws.com/list.html
