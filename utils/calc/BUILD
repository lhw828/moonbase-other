if module_installed readline; then
  make USE_READLINE="-DUSE_READLINE" READLINE_LIB="-lreadline" READLINE_EXTRAS="-lhistory -lncurses"
fi &&

default_make &&

gather_docs BUGS LIBRARY
