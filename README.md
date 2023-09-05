# AMIBS
 This is an adaptive mesh refinement code for incompressible flows

# COMPILE
Please go to the folder Exec and type "make". The executable file will be created under the extension ".ex".

You can also type "make -j4" or "make -j5" to use more CPUs for compiling, which makes the process faster

# VISUALIZATION

To visualize using the AMRVIS, you need to install the following packages in Ubuntu:

libmotif-dev			% amrvis
libvolpack1-dev		        % amrvis
libxext-dev			% amrvis
libxpm-dev			% amrvis
m4				% amrvis

Noe that the color pallete must be specified in the ./amrvis_defauls for the path

To visualize many files (movies), you need to do ./amrvis2d -a plt0*
