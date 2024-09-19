// convertVideo.js
const { exec } = require('child_process');

// Ruta del archivo de video a convertir (puedes modificar esto para aceptar argumentos)
const inputFile = './videos/input.mp4';
const outputFile = `./videos/esteban1245lhr_output.mp4`;  // Archivo de salida con tu nombre de usuario

// Comando de FFmpeg para convertir el video
const ffmpegCommand = `ffmpeg -i ${inputFile} -vcodec h264 -acodec mp2 ${outputFile}`;

// Ejecuta el comando de FFmpeg
exec(ffmpegCommand, (error, stdout, stderr) => {
    if (error) {
        console.error(`Error al convertir el video: ${error.message}`);
        return;
    }
    console.log(`Conversión exitosa: Archivo generado - ${outputFile}`);
})
