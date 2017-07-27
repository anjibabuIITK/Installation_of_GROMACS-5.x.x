# Installation_of_GROMACS-5.x.x MPI version

I have written detailed installation procedure in one of my previous blog.
Here i am giving that link as reference to follow step by step.

https://install-gromacs.blogspot.in/

The one can easily install gromacs parallel version by foolowing step by step procedure from above link.

But, 

After many observations , I have relized that there will be chances of endup with 
wrong installation or incomplete installation just because of incomplete installations
of CMAKE and FFTW.

Sometimes, It quite possible that, Installation may seems fine but, it may not generate 
all the required binary executables.

Example: CCMAKE is one of the important pre-requisite package to install gromacs. But ,
while installation of cmake sometimes , it only generates (cmake cpack ctest ) executables
instead of (ccmake  cmake  cpack  ctest ) , ccmake will miss some times.and with ccmake we 
can install gromacs without confusions.

Example2 : FFTW also one of important pre-requisite , In this case, sometimes may not
generate all the library files. 



So, To solve these two problems , above I am attaching those cmake binary executables, 
and FFTW library files. 

If anyone got similar errors or incomplete installations due to cmake or fftw. 
you can download these files and simply place in proper directories. Those will start work asuaslly.

CMAKE-bin : after installtion of cmake , place above files in PATH/ccmake-x.x/bin
FFTW-lib  : After installtion of fftw , place all the above lib files in PATH/fftw/lib 

now start installing gromacs by using procedure from above link.


Cheers..!!!!!!!


#================================================================================#
#                                                                                #
#                                  ANJI BABU KAPAKAYALA                          #
#                       NDIAN INSTITUTION OF TECHNOLOGY, KANPUR.                 #
#                                         INDIA.                                 #
#                               (anjibabu480@gmail.com)                          #
#                                                                                #
#================================================================================#



