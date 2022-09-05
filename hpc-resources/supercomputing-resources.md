# Supercomputing Resources

#### **Scaling tests** <a href="#supercomputeraccess-scalingtests" id="supercomputeraccess-scalingtests"></a>

See group meeting slides from 2022/05/25.

[Example write up for a project's scaling test](https://wikis.utexas.edu/download/attachments/360416757/XSEDE2018-WW.pdf?version=1\&modificationDate=1653437358790\&api=v2)

#### **Tips for running calculations:** <a href="#supercomputeraccess-tipsforrunningcalculations" id="supercomputeraccess-tipsforrunningcalculations"></a>

* **Always have a purpose for a submitted calculation:** e.g., convergence test, parameter test, new idea
* **Run small tests**: Whenever starting a new calculation or new calculation workflow, run a small test- a smaller system, a shorter requested calculation time, less stringent running parameters, etc. If possible, run on the debug/development queue to make sure everything will run through. This will save you much headache and lost time on failed runs that had long queue times.
* **If unsure, do a small scaling test**: Not all calculations run with the same efficiency with the same parallelization. This will also change depending on the cluster you run calculations on. To make sure you are using resources efficiently, get into the habit of running scaling tests.
* **Be mindful of the resources you use**: Some projects will involve a larger amount of resources, some projects will use an intermediate amount of resources. Be cognizant of the resources you used. If resources are running low (i.e., hours, disk space), let the everyone in the group know asap.&#x20;

#### Basic SLURM commands <a href="#supercomputeraccess-basicslurmcommands" id="supercomputeraccess-basicslurmcommands"></a>

SLURM is a scheduling resource manager that arranges all the submitted jobs on a cluster to run. Below are some basic commands; each has their own options and flags. Look to [SLURM documentation](https://slurm.schedmd.com/documentation.html) for further details.

* **srun**: initiate an executable (typically what is used to launch the executable)
* **sbatch**: submit a job to the cluster
* **scancel**: cancel a submitted job to the cluster
* **sacct:** retrieve job history and accounting (e.g., hours used, nodes used)
* **sprio**: view detailed components in job's priority
* **sinfo:** view the state of partitions and nodes managed by Slurm
* **squeue**: view the state of jobs or job steps (e.g., a queued/running job

[A more complete list of basic SLURM commands](https://slurm.schedmd.com/quickstart.html)
