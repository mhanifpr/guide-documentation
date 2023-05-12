# Resources

## Food
Food sangat penting untuk pertumbuhan kota dan pasukan Anda di Utopia. Anda memerlukan jumlah Food yang cukup untuk menjaga kestabilan populasi kota, membangun bangunan, dan melatih pasukan. Jika pasokan Food Anda menipis, kesehatan dan kekuatan pasukan akan menurun, sehingga membuat Anda lebih rentan terhadap serangan musuh. Pastikan untuk mempertahankan produksi makanan yang cukup agar kota Anda selalu berkembang dengan baik. Satuan Food adalah bushels

### Formula Food
:::caution Food Consume
Jika suatu provinsi tidak memiliki _`Food`_, maka provinsi tersebut akan mengalami kelaparan. Ketika provinsi mengalami kelaparan, jumlah populasi di dalamnya (petani, pasukan militer, dan pencuri) akan berkurang seiring dengan besarnya kekurangan makanan (termasuk pasukan yang sedang berada di luar provinsi). Namun, para penyihir tidak akan terpengaruh oleh kondisi kelaparan. Tingkat kematian akibat kelaparan ini dibatasi maksimal 5% dan akan berlanjut sampai nilai makanan di provinsi tersebut lebih besar dari 0.
`/Bushels Eaten = Total Population * 0.25 * [Race Mod](http://wiki.utopia-game.com/index.php?title=Race "Race") * [Gluttony Mod](http://wiki.utopia-game.com/index.php?title=Mystics#Gluttony "Mystics")`
:::

## Income and Networth
>**Money** sangat penting di permainan Utopia karena dibutuhkan untuk membangun berbagai bangunan dan tentara. Uang juga digunakan untuk membayar gaji pekerja, pasukan, dan pelayan. Jika kamu tidak memiliki cukup uang, kamu akan kesulitan untuk mempertahankan kerajaanmu.

>**Networth** dalam permainan Utopia adalah sebuah metrik yang mengukur kemakmuran suatu pemain dalam permainan. Itu dihitung dari total nilai semua aset yang dimiliki oleh pemain di provinsi mereka, termasuk pasukan, bangunan, dan sumber daya.

--- 

### Formula Income dan Networth

:::tip Money
```
/Raw Income = (3 * Employed Peasants) + (1 * Unemployed Peasants) + (0.75 * Prisoners) + Racial Gold Generation + ([[Banks]] * 25 * [[buildings efficiency]]) + Miner's Mystique Gold Generation`

/Modified Income = Raw Income  * * [Plague](http://wiki.utopia-game.com/index.php?title=The_Plague "The Plague")  * * [Riots](http://wiki.utopia-game.com/index.php?title=Thievery#Incite_Riots "Thievery") * * Bank % Bonus * * Income Sci * * [Honor Income Mod](http://wiki.utopia-game.com/index.php?title=Honor#Effects "Honor") * * Race Mod * * Personality Mod * * Dragon* * Ritual`
```
:::

:::tip Networth 
```
/Total Networth =  (Peasants* 0.25) + (Soldiers * Soldier NW) + (Off Specs * Offspec NW) + (Def Specs * Defspec NW) + (Elites * Elite NW) + (Money / 1000) + (Horses * Off value * 0.3) + (Prisoners * Off value * 0.2) + (Thieves * 5) + (Wizards * 5) + (Books * 0.000007 * Acres) + (Barren Land * 40) + (Buildings * 60) + (Buildings in Progress * 50)
```
:::