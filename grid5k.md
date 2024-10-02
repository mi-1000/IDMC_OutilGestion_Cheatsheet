Most OAR commands (oarsub, oarstat, oarnodes) can provide output in various formats:
- text (this is the default mode)
- PERL dumper (-D)
- XML (-X)
- Yaml (-Y)
- json (-J)

1. oarsub : this command is used to reserve resources for a job.
2. oarstat : this command allows you to check the status of jobs in the system.
3. oarnodes : you can use this to check the availability of resources.

We have also : oardel (cancel a running or waiting job)