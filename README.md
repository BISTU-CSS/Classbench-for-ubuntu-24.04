# Classbench-for-ubuntu-24.04
Available Classbench for ubuntu-24.04 LTS

#requirements
make; git; build-essential; 

#1.MAKE

cd classbench/classbench-ng/vendor

make



#RUN

cd db_generate

./db_generator -c ../parameter_files/acl1_seed 1000 0 0 0 acl1_1000
