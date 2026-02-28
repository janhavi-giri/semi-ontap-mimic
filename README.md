# ONTAP mimic: Supervised Semiconductor Defect Image Classification (CRISP‑DM) 

# **End‑to‑end data flow + ONTAP “equivalent primitives” (Snapshots, FlexClone, FlexGroup)**

 NetApp ONTAP concepts referenced (production equivalents)

* Snapshot copies (dataset/model lineage + rollback): https://docs.netapp.com/us-en/ontap/concepts/snapshot-copies-concept.html

* FlexClone (space‑efficient dataset branching): https://docs.netapp.com/us-en/ontap/volumes/flexclone-efficient-copies-concept.html

* FlexGroup (scale‑out NAS for throughput + metadata heavy workloads): https://docs.netapp.com/us-en/ontap/flexgroup/definition-concept.html

## What this notebook demonstrates:
* A standard CRISP‑DM workflow for semiconductor image classification 
* Where data friction appears (ingest, cleaning, iteration, throughput) 
* How ONTAP primitives map to the same bottlenecks in production

**Colab cannot run ONTAP directly for every customer; this demo shows the mechanisms and maps them to ONTAP features used in real deployments.** 
