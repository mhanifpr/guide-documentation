
Jadi, dalam game Utopia, kita harus memastikan bahwa penduduk desa kita memiliki pekerjaan agar bisa mendapatkan uang. Setelah kita membangun tanah kita, penduduk desa akan bisa mencari pekerjaan. 

:::info Pekerjaan
>Ada beberapa bangunan yang bisa memberikan pekerjaan, kecuali rumah yang tidak memberikan pekerjaan. Setiap bangunan selain rumah memberikan 25 pekerjaan, dan setiap penduduk desa bisa bekerja 1,5 pekerjaan.
:::

>Kita bisa melihat jumlah pekerjaan yang tersedia, jumlah pekerja yang tersedia, dan jumlah pekerja yang dibutuhkan untuk memaksimalkan efisiensi bangunan dengan menggunakan Building Advisor. Dengan begitu, kita bisa mengatur pekerjaan dengan baik dan memastikan perekonomian desa kita sehat.

---
## Formula

:::tip Available Jobs
`/Available Jobs = (Completed Buildings - Homes) * 25`
:::

:::tip Unfilled Jobs
`/Unfilled Jobs =** _MAX_ ( Available Jobs - Peasants - _ROUNDDOWN_( Prisoners / 2 ) , 0 )`
:::

:::tip Employed Peasants
`/Employed Peasants =** _MIN_ ( Peasants - Available Jobs - _ROUNDDOWN_ ( Prisoners* / 2 ) )`
:::

:::tip Unemployed Peasants
`/Unemployed Peasants = MIN(Peasants - Employed Peasants`
:::

:::tip Employment Rate
`/Employment Rate = (Employed Peasants / Peasants) * `
:::
