setcpm(91/4)
$: s("pulse").note(`<E3 A3 C4 E3 A3 C4 E3 A3 D3 G3 B3 D3 G3 B3 D3 G3 C3 F3 A3 C3 F3 A3 C3 F3 D3 F3 A3 D3 F3 A3 D3 F3>`).fast(8)
.lpf(327).resonance(6).lpd(.17).lpa(.03).pw(.6).delay(".18:.15:.25:.2").diode("2.4:.4").orbit(2).mask("<1!8 0!8>")
$: s("pulse")
  .note(`<F3 A3 C4 F3 A3 C4 F3 A3
          G3 B3 D4 G3 B3 D4 G3 B3
          E3 G3 B3 E3 G3 B3 E3 G3
          F3 A3 C4 F3 A3 C4 F3 A3>`)
.fast(8).lpf(367).resonance(6).lpd(.17).lpa(.03).pw(.6).delay(".18:.15:.25:.2").diode("2.4:.5").orbit(2).mask("<0!8 1!8>")
$: note("<A2!3 [~ B2] B2!3 [G2 F2] F2!3 [E2 D2] D2!3 [B1 A2]>").vel(.96)
  .s("pulse").fast(4).lpf(226).diode("2.4:.6").lpd(.9).orbit(2).mask("<1!8 0!8>").lpd(.8)
$: note("<F2!3 [~ G2] G2!3 [~ E2] E2!3 [~ F2] F2!3 [~ F2]>")
  .s("pulse").fast(4).lpf(326).diode("2.4:.6").lpd(.9).orbit(2).mask("<0!8 1!8>")
$: s("bd:2!4").room("<0 .09>".fast(4)).soft(.7).postgain(.99).duckatt(.1).duckorbit(2).lpf(4999)
$: s("<~ sd:4>".fast(4)).vel(.4).room(.2)
$: note("< [F5,A5,C5]!3 [~ ] [G5,B5,D5]!3 [~ ] [E5,G5,B5]!3 [~ ] [F5,A5,C5]!3 [~ ] >")
  .early("<0 .5 .5 .5>".slow(2)).vel(.6)
  .s("sawtooth").detune(-.5).fast(4).att(.1).bpf(156).diode("1.9:.5").rel(.4).bpa(.1).bpd(.9).orbit(2).mask("<0!8 1!8>")
