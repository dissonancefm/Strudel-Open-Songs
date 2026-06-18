# Strudel-Open-Songs
Open-Source Songs for Strudel.cc

TWIN PEAKS :

setcpm (288/4)
$: s("gm_epiano1")
  .note("<F2 [G4,A4,C5] ~ ~ D3 [E4,F4,A4] D4 ~>")
  .clip("<2>").vel(.5).rel(.8).n(5).diode(".7:1.8").pan(.4).delay(".3:.5:.4:.34").mask("<1@32 0@32>").v(5).vmod(.1).bpf("645:2")
$: s("gm_epiano1")
  .note("<F3 C4 [C4,G4,A4,C5] F4 D3 A3 [E4,F4,A4] D4>")
  .clip("<1 .8 2 1>").vel(.4).rel(.5).n(5).diode(".7:1.8").pan(.4).delay(".2:.6:.5:.4").mask("<0@32 1@32>").v(5).vmod(.1).bpf("645:2")
$: s("gm_synth_choir,gm_synth_strings_2,gm_synth_brass_2").note("<~@22 D5@2 E5@2 F5@2 G5@2 A5 A#5>").vel(.4)
  .n(3).diode(".7:.4").bpf("945:2").rel("<1.2>").pan(.55).mask("<1@32 0@32>").v(5).vmod(.1)
$: s("gm_synth_choir,gm_synth_strings_2,gm_synth_brass_2").note("<[G5,A5,C6] ~@3 [E5,F5,A5] ~@3>").vel(.4)
  .n(3).diode(".7:.4").bpf("945:2").att(.2).rel("<3.3>").pan(.55).mask("<0@32 1@32>").v(5).vmod(.1)
$: s("gm_acoustic_bass")
  .note("<F3 ~ ~ ~ ~ ~ ~ C3 D3 ~ ~ ~ ~ ~ ~ ~>").n(1)
  .fast(2).diode("1.1:.8").lpf("2445:2").rel("<1.7!3 .8 1.7!4>")
  .trem(8).tremdepth(.8).tremskew(.4).pan(.6).mask("<1@32 0@32>")
$: s("gm_acoustic_bass")
  .note("<~ C3 F3 G3 A3 G3 F3 C3 D3 ~ ~ ~ ~ ~ ~ ~>").n(1)
  .fast(2).diode("1.1:.7").lpf("2445:2").rel("<.1!6 1.3!6>")
  .trem(8).tremdepth(.8).tremskew(.4).pan(.6).mask("<0@32 1@32>")
$: s("gm_electric_guitar_jazz").note("<F3 ~ ~ ~ ~ ~ ~ C3 D3 ~ ~ ~ ~ ~ ~ ~>").n(1)
  .fast(2).diode(".7:.7").hpf("545:2").rel("<1.1!3 .8 1.3!4>")
  .trem(8).tremdepth(.8).tremskew(.4).v(.1).chorus(.6).pan(.6).mask("<1@32 0@32>")
$: s("gm_electric_guitar_jazz").note("<~ C3 F3 G3 A3 G3 F3 C3 D3 ~ ~ ~ ~ ~ ~ ~>").n(1)
  .fast(2).diode(".7:.7").hpf("545:2").rel("<.1!4 1.3!4>")
  .trem(8).tremdepth(.8).tremskew(.4).v(.1).chorus(.6).pan(.6).mask("<0@32 1@32>")
$: s("gm_sitar").note("<F3 ~ ~ ~ ~ ~ ~ C3 D3 ~ ~ ~ ~ ~ ~ ~>")
  .n(2).fast(2).diode(".7:.5").hpf("645:2").rel("<1.1!3 .8 1.3!4>")
  .trem(8).tremdepth(.8).tremskew(.4).v(.1).chorus(.6).pan(.6).mask("<1@32 0@32>")
$: s("gm_sitar").note("<~ C3 F3 G3 A3 G3 F3 C3 D3 ~ ~ ~ ~ ~ ~ ~>@2")
  .n(2).fast(2).diode(".7:.5").hpf("645:2").rel("<.1!4 1.3!4>")
  .trem(8).tremdepth(.8).tremskew(.4).v(.1).chorus(.6).pan(.6).mask("<0@32 1@32>")



