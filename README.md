﻿# python-word-count-beam

# Set up your Environment
Check your python version by using the command: python --version
python -m pip install --upgrade pip

# Get Apache Beam
python -m venv C:\path\to\directory
C:\path\to\directory\Scripts\activate.ps1

# Download and Install
python -m pip install apache-beam

# Execute a pipeline
python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts

After the pipeline completes, you can view the output files at your specified output path. For example, if you specify /dir1/counts for the --output parameter, the pipeline writes the files to /dir1/ and names the files sequentially in the format counts-0000-of-0001.
