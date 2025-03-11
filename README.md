Repositório oficial do programa "mtPaint"


GitHub do mtPaint

https://github.com/wjaguar/mtPaint/


Página eletrônica do mtPaint

https://mtpaint.sourceforge.net/


Manual do mtPaint (em idioma inglês)

https://mtpaint.sourceforge.net/handbook/en_GB/chap_00.html

- - - - -

Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/mtPaint_pt_BR/mtpaint_pt_BR.po

https://github.com/marcelocripe/mtPaint_pt_BR/mtpaint.desktop


Para utilizar o arquivo "mtpaint_pt_BR.po" e o "mtpaint.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"mtpaint_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt mtpaint_pt_BR.po -o mtpaint.mo

Comando para renomear o arquivo antigo da tradução com a extensão ".mo" que está na pasta do idioma "pt_BR".

$ sudo mv /usr/share/locale/pt_BR/LC_MESSAGES/mtpaint.mo /usr/share/locale/pt_BR/LC_MESSAGES/mtpaint_antigo.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp mtpaint.mo /usr/share/locale/pt_BR/LC_MESSAGES


"mtpaint_pt_BR.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp mtpaint_pt_BR.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
