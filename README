
SimpleMPI
==========

A friendly wrapper for mpi4py that allows maps to run on each mpi thread. 

Importing MPI_Map.MPI_Map will allow easy parallel mapping:

	y = MPI_map(f, range(1500))

where each job is sent to a separate core, when started like:

	mpirun -n 4 python MPI_map.py


To time on a simple test:

time mpirun -n 2 python MPI_map.py

time mpirun -n 10 python MPI_map.py

REQUIREMENTS
=============

	mpi4py (apt-get install works best when mpich2 is also apt-get installed)
	multiprocessing (for parallel buffered i/o on the host)
	lockfile
	
INSTALLATION:
=============

Put this library somewhere--mine lives in /home/piantado/Libraries/SimpleMPI/
	
Set the PYTHONPATH environment variable to point to SimpleMPI/:
	
	export PYTHONPATH=$PYTHONPATH:/home/piantado/Desktop/Libraries/SimpleMPI
	
You can put this into your .bashrc file to make it loaded automatically when you open a terminal. On ubuntu and most linux, this is:
	
	echo 'export PYTHONPATH=$PYTHONPATH:/home/piantado/Desktop/Libraries/SimpleMPI' >> ~/.bashrc

And you should be ready to use the library
