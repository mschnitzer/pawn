Download binaries for Linux and Windows here:

  https://github.com/Zeex/pawn-3.2.3664_patches/tree/downloads

If you want to build the compiler manually:

  wget http://www.compuphase.com/pawn/pawn-3.2.3664.zip
  unzip pawn-3.2.3664.zip
  cd SOURCE
  mv AMX amx
  mv LINUX linux
  cd COMPILER
  git clone git://github.com/Zeex/pawn-3.2.3664_patches.git patches
  cd patches
  ./apply_compatible.sh ../../
  cmake ../
  make