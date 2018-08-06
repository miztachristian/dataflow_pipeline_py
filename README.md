# dataflow_pipeline_py
GCP Dataflow pipeline in python \
\
as per https://codelabs.developers.google.com/codelabs/cpb101-simple-dataflow-py \
and per https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/data_analysis/lab2/python \
and per https://www.udemy.com/gcp-data-engineer-and-cloud-architect/learn/v4/t/lecture/7598612?start=0 \
\
\
reads files and outputs lines which contain search query (regex)

### install_packages.sh
list of pkgs

### grep_pipeline_local.py
for local deploy

### grep_pipeline_cloud.py
for dataflow deploy \
reads and writes to Cloud Storage bucket \
note BUCKET_ID & PROJECT_ID vars
