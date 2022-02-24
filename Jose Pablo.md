## Uso
- git clone 
- conda env create -f environment.yml
- conda activate warpq
- python WARPQ_demo.py -m -i "Carpeta de archivos a procesar" -r "Audio de referencia" (subfolders separados con \\) (-m para procesar con multiples nucleos)
Ejemplo:
python WARPQ_demo.py -m -i "E:\\Trascender_Global\\Voice Cloning - Delsec\\WARP-Q\\WARP-Q\\audio" -r "E:\\Trascender_Global\\Voice Cloning - Delsec\\audios test\\jose\\test.wav"
- Resultados en ultima columna Results.csv o impresos en terminal