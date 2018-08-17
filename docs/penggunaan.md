# Penggunaan

## Memulai

Anda dapat mengunduh *repository* ini dengan cara manual atau
menggunakan `git clone`

``` bash
$ git clone https://gitlab.com/template-tugasakhir-latex/template-proposal-latex
```

Silahkan `checkout` *branch* yang anda inginkan. *untuk saat ini hanya
branch filkom yang tersedia*

## Ekspor ke PDF

Anda dapat mengekspor ke PDF dengan cara:

``` bash
xelatex proposal.tex
```

Atau menggunakan *bash script* yang kami sediakan

``` bash
chmod +x compile-latex.sh
./compile-latex.sh
```

Anda dapat menghapus berkas aux yang dihasilkan latex dengan `delete-aux.sh`

