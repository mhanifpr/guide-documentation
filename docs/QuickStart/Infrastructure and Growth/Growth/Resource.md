# Resources

## Food
Food sangat penting untuk pertumbuhan kota dan pasukan Anda di Utopia. Anda memerlukan jumlah Food yang cukup untuk menjaga kestabilan populasi kota, membangun bangunan, dan melatih pasukan. Jika pasokan Food Anda menipis, kesehatan dan kekuatan pasukan akan menurun, sehingga membuat Anda lebih rentan terhadap serangan musuh. Pastikan untuk mempertahankan produksi makanan yang cukup agar kota Anda selalu berkembang dengan baik. Satuan Food adalah bushels

:::caution Food Decayed
Dalam kondisi normal, sekitar 0,99 atau sekitar 1% dari total stok makanan akan _`rusak`_. Jumlah yang tepat tergantung pada pengubah dalam rumus yang telah diberikan di atas dan dihitung berdasarkan total makanan yang disimpan di provinsi. Jadi jika sebuah provinsi memiliki 300.000 gantang makanan dalam stok dalam kondisi normal, maka penurunan yang diharapkan sedikit lebih atau kurang dari 3000 gantang per tick / hari Utopia. Terkadang, jumlah makanan yang rusak bisa lebih tinggi daripada yang tersisa setelah makanan yang dibutuhkan oleh populasi dikonsumsi dari hasil pertanian.
:::
:::caution Food Consume
Jika suatu provinsi tidak memiliki _`Food`_, maka provinsi tersebut akan mengalami kelaparan. Ketika provinsi mengalami kelaparan, jumlah populasi di dalamnya (petani, pasukan militer, dan pencuri) akan berkurang seiring dengan besarnya kekurangan makanan (termasuk pasukan yang sedang berada di luar provinsi). Namun, para penyihir tidak akan terpengaruh oleh kondisi kelaparan. Tingkat kematian akibat kelaparan ini dibatasi maksimal 5% dan akan berlanjut sampai nilai makanan di provinsi tersebut lebih besar dari 0.
:::

----

### Formula Food

:::tip Food Consume
```
/Bushels Eaten = Total Population * 0.25 * [Race Mod] * [Gluttony Mod]
```
:::

:::tip Food Produce
```
/Base Food Production     = (([[Farms]]* 60) * [[Building Efficiency]]) + ([[Barren Land]] * 2) + (Race Mod * Acres) + ([[Personality Mod]] * Acres)

/Modified Food Production = Base Food Production * [Production Science Mod] * [Fertile Lands Mod] * [Drought Mod]
```
:::

## Income and Networth
>**`Money`** sangat penting di permainan Utopia karena dibutuhkan untuk membangun berbagai bangunan dan tentara. Uang juga digunakan untuk membayar gaji pekerja, pasukan, dan pelayan. Jika kamu tidak memiliki cukup uang, kamu akan kesulitan untuk mempertahankan kerajaanmu.

>**`Networth`** dalam permainan Utopia adalah sebuah metrik yang mengukur kemakmuran suatu pemain dalam permainan. Itu dihitung dari total nilai semua aset yang dimiliki oleh pemain di provinsi mereka, termasuk pasukan, bangunan, dan sumber daya.

--- 

### Formula Income dan Networth

:::tip Money
```
/Raw Income = (3 * Employed Peasants) + (1 * Unemployed Peasants) + (0.75 * Prisoners) + Racial Gold Generation + ([[Banks]] * 25 * [[buildings efficiency]]) + Miner's Mystique Gold Generation`

/Modified Income = Raw Income  *  [Plague] * [Riots] * Bank% Bonus  * Income Sci * * [Honor Income Mod] * Race Mod * * Personality Mod * * Dragon* * Ritual
```
:::

:::tip Networth 
```
/Total Networth =  (Peasants* 0.25) + (Soldiers * Soldier NW) + (Off Specs * Offspec NW) + (Def Specs * Defspec NW) + (Elites * Elite NW) + (Money / 1000) + (Horses * Off value * 0.3) + (Prisoners * Off value * 0.2) + (Thieves * 5) + (Wizards * 5) + (Books * 0.000007 * Acres) + (Barren Land * 40) + (Buildings * 60) + (Buildings in Progress * 50)
```
:::

## Runes
Runes adalah Sumber Daya utama untuk melakukan Spell Cast.

 
:::info Obtaining Runes
bangunan _`Towers`_ dapat memproduksi Runes tiap 1 hari dalam Utopia
    
> :::caution
Runes juga dapat diambil oleh musuh, via:
 - [_`Plunder Attack`_](http://wiki.utopia-game.com/index.php?title=Military#Plunder) 
 - [_`Thief Ops`_](http://wiki.utopia-game.com/index.php?title=Thievery#Rob_the_Towers)
:::

### Decay and Destruction
Setelah setiap _`tick`_, 1,2% dari total rune yang disimpan akan membusuk.

Pasokan rune provinsi musuh dapat diserang melalui Mantra Serangan Petir. Serangan ini tidak akan memberikan rune yang hancur kepadamu.

