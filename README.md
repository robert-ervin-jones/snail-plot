1. Create a conda environment for blobtools2 using the yaml file:<br>
`mamba env create -n blobtools2 -f blobtools2.yaml`

2. Activate the environment:<br>
`conda activate blobtools2`

3. Create blob database from the genome assembly:<br>
`blobtools add --create --fasta path/to/assembly.fasta /path/to/blobDB`

4. Make snail plot:<br>
`blobtools view --plot --format svg --view snail /path/to/blobDB`