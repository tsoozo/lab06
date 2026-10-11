**# Лаб 6: Category-Partition ба PICT**



**\*\*Оюутны нэр:\*\* Б.Хишигцогзол**

**\*\*Оюутны код:\*\* B222270834**



**## Алхам 1: PICT-ийг эх кодоос бүтээх**



**Орчин: Windows, MSYS2 UCRT64 (g++). PICT-ийн эх кодыг лабын репоос гадна `\~/tools/pict`-д clone хийсэн. Энэ орчинд `cmake`, `make` суугаагүй тул PICT-ийн `Makefile`-ийн хийдэг хөрвүүлэлтийг `g++`-ээр шууд ажиллуулсан:**



**```bash**

**mkdir -p \~/tools \&\& cd \~/tools \&\& git clone https://github.com/microsoft/pict \&\& cd pict**

**g++ -std=c++11 -O2 -Iapi api/\*.cpp cli/\*.cpp -o pict.exe**

**mkdir -p \~/bin \&\& cp pict.exe \~/bin/**

**```**



**Нотолгоо: `results/pict-build.txt` (pict commit `ab76c25`, хэрэглээний заавар).**

