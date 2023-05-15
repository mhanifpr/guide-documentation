# Population

### Populasi
Sebagai pemimpin kami yang terhormat,  Anda harus  menemukan keseimbangan yang tepat antara ekonomi dan militer kami. Terlalu sedikit pasukan, dan kita mungkin mendapati diri kita terlalu terbuka terhadap ancaman luar dari musuh kita. Pasukan terlalu besar, dan petani kita akan berjuang untuk menghasilkan pendapatan yang dibutuhkan untuk membayar mereka.

:::caution warning
>Saat Provinsi tumbuh besar, populasi maksimum kami meningkat, memungkinkan kami untuk membangun dan memperkuat. Namun, petani dan militer kita akan segera menjadi tidak puas jika kita tidak lagi memiliki ruang hidup yang memadai, dan rakyat kita akan mulai meninggalkan tanah kita. 
>- Jika kita menjadi kelebihan populasi secara signifikan, kita akan menemukan bahwa militer dan pencuri kita menolak untuk bekerja, dan para petani kita akan melakukan kerusuhan di jalanan. 
>- Jika kita kehilangan semua petani kita, tanah kita akan runtuh dan hancur. Mengelola populasi kita dengan hati-hati adalah bagian penting dari memerintah sebuah provinsi di Utopia.
:::
---
### Formula

:::tip Total Population

```
/Raw [[Living Space]] = ((Built Land + Land in progress) * 25) + ( Barren Land .  15) + ([[Homes]] * [[Homes]] Capacity) 
```

```
/Mod [[Living Space]] = (((Raw Living Space - Homes Bonus) * Race Bonus) + Homes Bonus) * Population Science * Honor Population Bonus
```
>
>:::info Note
> > `Honor Bonuses are calculated as 1 + (Personality Mod * Honor Bonus)`
:::

:::tip Current Population
```
/Current Population = [[Peasants]] + [[Soldiers]] + Off Specs + Off Specs in Training + Def Specs + Def Specs in Training + Elites + Elites in Training + Thieves + Thieves in Training + Wizards
```
>:::info Note
> Prisoners do not add to the population
:::