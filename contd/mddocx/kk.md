# archi -> /Applications/Archi.app/Contents/MacOS/Archi
# echo "Archi -application com.archimatetool.commandline.app -consoleLog -nosplash \
#    --modelrepository.loadModel $rutamodelo \
#    --script.runScript $rutaprg/$prg \
#    -vistaDocumental $vistadoc \
#    -rutaMacMD $rutaMacMD \
#    -rutaCompleta $rutaCompleta"
/opt/Archi/Archi -application com.archimatetool.commandline.app -consoleLog -nosplash \
   --modelrepository.loadModel $rutamodelo \
   --script.runScript $rutaprg/$prg \
   -vistaDocumental $vistadoc \
   -rutaMacMD $rutaMacMD \
   -rutaCompleta $rutaCompleta