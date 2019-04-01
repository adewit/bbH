# bbH
for bbH grid-pack generation, one needs to use model file provided on github with label = "modified.tar.gz". These process folder was modified to take path of other files (lhapdf-config etc) automatically according to cmssw environment.
All the instructions for bbH_yb2 grid-pack are give in bbH-gridpacks.sh file. Follow these manually.
For bbH_ybyt, instructions are same. The only changes are:
1. https://github.com/panwarlsweet/bbH/blob/MG5_v2.6/bbH-gridpacks.sh#L23 . use bbH_ybyt tar filename here
2. https://github.com/panwarlsweet/bbH/blob/MG5_v2.6/launch_mg_jobs.py#L16 replace the base name with ./bbH_4FS_ybyt
