.. image:: https://travis-ci.org/brianjking/sphinx-test.svg?branch=master
    :target: https://travis-ci.org/brianjking/sphinx-test

.. image:: https://readthedocs.org/projects/bk-test/badge/?version=latest
:target: http://bk-test.readthedocs.org/en/latest/?badge=latest
:alt: Documentation Status
                

## TEST

Using Pandoc to auto-convert Markdown to ReStructuredtext (.rst) files to use with Sphinx.

#!/usr/bin/env python
import os
import subprocess

DOCUMENTATION_SOURCE_DIR = 'documentation/source/'
SOURCE_EXTENSION = '.md'
OUTPUT_EXTENSION = '.rst'

for _, __, filenames in os.walk(DOCUMENTATION_SOURCE_DIR):
    for filename in filenames:
        if filename.endswith('.md'):
            filename_stem = filename.split('.')[0]
            source_file = DOCUMENTATION_SOURCE_DIR + filename_stem + SOURCE_EXTENSION
            output_file = DOCUMENTATION_SOURCE_DIR + filename_stem + OUTPUT_EXTENSION
            command = 'pandoc -s {0} -o {1}'.format(source_file, output_file)
            print(command)
            subprocess.call(command.split(' '))


            via: http://www.pythonbackend.com/topic/1268949527



            <script src="https://gist.github.com/brianjking/e4a9176a05c0ec0ac40f.js"></script>
