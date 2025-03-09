Hexreplace sirve para reemplazar codigo hexadecimal utilizando comodines ??
compilado en c++


Se recomienda respaldar el archivo a cambiar y usar fc para comparar para verificar que ha sido aplicado el cambio hexadecimal

echo T|copy file.bin file.bak

hexreplace_x64_v1.2.exe file.bin "90 00 ?? ?? 00 " "90 00 01 01 00"

fc /b file.bin file.bak
