# Buildings and Their Effect

Hai! Utopia adalah sebuah game online yang menantang di mana kamu bisa membangun provinsimu sendiri. Salah satu elemen penting di dalam game ini adalah bangunan-bangunan.

>Bangunan-bangunan ini sangatlah penting karena mereka memberikan berbagai manfaat bagi kerajaanmu, seperti meningkatkan produksi sumber daya, meningkatkan pertahanan militer, dan bahkan meningkatkan kemampuan sihir.

---

## Buildings

Berikut adalah beberapa  [**`bangunan`**](https://www.notion.so/2bdab2ed52c04b72a15c0ac90895753b?v=1b8983ca18b1412a9015b56010d8b44e&pvs=4) di Utopia:

No.| Buildings Name| No.| Buildings Name
---|----------------|---|----------------
1.| Armouries |11.| Library
2.|Banks |12.| Military Barracks
3.|Barren Land| 13.| Mills
4.| Dungeons| 14.| Stables
5.|Farms| 15.|Thieves Dens
6.|Forts|16.|Towers
7.|Guard Station|17.|Training grounds
8.|Guilds|18.|University
9.|Homes|19.|Watch Towers
10.|Hospitals|

>Dengan membangun dan mengelola bangunan-bangunan ini dengan bijak, kamu dapat membangun kerajaan yang sukses dan kuat di Utopia. Selamat mencoba dan jangan lupa untuk bermain dengan cerdas dan bijak!

--------
### The Buildings 
<details>
  <summary>Armouries</summary>
  <div>
<div>
tempat dimana senjata dan peralatan militer disimpan dan dikelola. Ini biasanya digunakan oleh pasukan atau angkatan bersenjata untuk memastikan bahwa mereka memiliki persenjataan yang dibutuhkan saat diperlukan.
<br/>
percentBaseEffect. : decr 2% draft cost, decr 2% wages, decr 1.5% training cost
percentMax         : 50%, 50%, 37.5%
living space       : 25
jobs               : 25
<hr/>
Percent-Based effect
</div>
</div>
    <br/>
    </details>  
--------
### Buildings Effect

Masing-masing bangunan yang ada pada Utopia-game memiliki efek yang berbeda terhadap provinsimu. Yang dibagi menjadi 3 jenis yaitu: 

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

:::tip Jenis Efek terhadap Buildings
<!-- <Tabs>
  <TabItem value="capacityBuildings" label="Capacity Buildings">These buildings simply create space for you, and are not impacted by efficiency
issues. Homes, for example, provide additional space for peasants.</TabItem>
  <TabItem value="flatRateBuildingss" label="Flat Rate Buildings">This type of building provides a set amount of a particular resource. These
buildings need many employees to be fully effective. These buildings are impacted by building efficiency. An example is a Tower which creates a set
number of runes each day.

/Flat Rate Buildings= Base Effect Number of Buildings (1 + Race) * BE</TabItem>
  <TabItem value="percentageBasedBuildings" label="Percentage-based Buildings">The majority of Utopian buildings are percentage-based. These buildings
provide an effect based on the portion of your land covered by it. For example, having 10% of your land as Banks will increase your income by a certain percentage. Like flat-rate buildings, these also require employees to provide full effects. In addition, each additional building you construct will be less effective. The numbers listed in this section would be for the first building you construct. Your Internal Affairs Advisor will help you to understand the benefits of your land.
Unless otherwise specified, these buildings have a maximum effect of 25 times the number listed below. With normal building efficiency, this maximum is reached by dedicating 50% of your land to that building.

/Percentage Based Buildings = Base Effect BE MIN(50%, % of building (1 + Race)) (100% - MIN(50%, % of building * (1 + Race)))</TabItem>
</Tabs> -->
> 1. [[Capacity Buildings]]
>2. [[Flat Rate Buildings]]
>3. [[Percentage-based Buildings]]
:::
-----

### Buildings Formula

:::tip Efisiensi pekerja terhadap bangunan yang dimiliki
```
/Available Workers =  Peasants + _ROUNDDOWN_ ( Prisoners / 2 )
```
```
/Optimal Workers = _ROUNDDOWN_ ( Total Jobs * 0.67 )
```
```
/% Jobs Performed =  _MIN_ ( Available Workers / Optimal Workers,1 )
```
```
/buildings efficiency =  (0.5 * (1 + % Jobs Performed)) * Race * Personality * Tools Science * Dragon * Blizzard
```
:::

