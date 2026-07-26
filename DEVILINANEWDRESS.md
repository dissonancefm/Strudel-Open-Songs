setcpm(80/4)
samples('github:dissonancefm/samples')
$: s("sample27").adsr("0:0:1:0").loopAt(16).scope().soft(2).gain(.16).delay(".2:.2:.3:.3")
$: s("b12,b8").loopAt(2).gain(.5).scope().gain(.5)
$: s("bd:6!16").degradeBy(.8).rib(1,834).soft(.6).gain(.99)
$: s("bd:6,12!16").struct("x ~ ~ ~ ~ ~ ~ x ~ ~ ~ x ~ ~ ~ x").speed(.96).soft(.3).gain(.99)
$: s("~ sd:7").fast(2).speed(.88).gain(.6)
$: s("hh:7!8,hh:5!8").speed(.9).gain(.57)
/*
@title:devildress
@by:ye devildress
song @by ye devildress
*/
