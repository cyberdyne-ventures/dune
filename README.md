![things](/img/dune.jpg?raw=true "text")  
# DUNE 
### (discovery of novel unseen events)
A project for threat hunting using a combination of anomaly detection, machine learning, and specification-based detection. The first release is focused on hunting using cloudtrail events. 

Contents

Jupyter

- an ensemble notebook using pyod to do anomaly detection
- a notebook using k-means to do anomaly detection
- a notebook containing a proof of concept of a compression / de-duplication method for threat hunting in cloudtrail events
- a sanatized cloudtrail dataset containing a few target outlier events, which these notebooks process by default

Dashboards

- a dashboard using the 'significant terms' function for anomaly detection in cloudtrail events
