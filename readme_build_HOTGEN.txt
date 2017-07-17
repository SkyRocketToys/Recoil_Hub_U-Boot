Build the uboot binaries :-
---------------------------

export TOOLCHAIN_DIR=${PWD}/toolchain
export PATH=${TOOLCHAIN_DIR}/bin:${PATH}
make openembed_som9331
ls -l bin

