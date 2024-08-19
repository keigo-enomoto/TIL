
## Grand Canonical Montecarlo 法

- 化学ポテンシャル : $ \mu = \mu_{id} + \mu_{ex}$ , $\mu_{ex}$ は [Widom insertion method](https://en.wikipedia.org/wiki/Widom_insertion_method) か [熱力学積分法](https://ja.wikipedia.org/wiki/%E7%86%B1%E5%8A%9B%E5%AD%A6%E7%9A%84%E7%A9%8D%E5%88%86%E6%B3%95)で計算することができる。
- Widom insertion methodは、 test particleを系に入れて、エネルギーの変化を見る手法。 LAMMPSにも実装されている [fix/widom](https://docs.lammps.org/fix_widom.html)
- 熱力学積分は、相互作用パラメータなどを変化させた際のpotential mapから自由エネルギーを計算する手法。パラメータの変化に対して可逆的なpotential mapが描けるかがポイント。 Material Studioで計算できる



## Reference

- [Understanding Molecular Simulation](https://www.eng.uc.edu/~beaucag/Classes/AdvancedMaterialsThermodynamics/Books/%5BComputational%20science%20(San%20Diego,%20Calif.)%5D%20Daan%20Frenkel_%20Berend%20Smit%20-%20Understanding%20molecular%20simulation%20_%20from%20algorithms%20to%20applications%20(2002,%20Academic%20Press%20)%20-%20libgen.lc.pdf)
Frenkelの書いた素晴らしい良書




