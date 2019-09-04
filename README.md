    \version "2.19.82"
    
    RHI = \relative c' {
      \key c\minor
      \time 3/4
      \voiceOne r8. <es g>16 <c' es>4.. <b d>16 |
      c8. g16 <es' g>4.. <d f>16 |
      <c es>8. c16 <es c'>4.. <g bes>16 |
      <c, f aes>4 <c es g> r4 |
      des,8.( c16) des8.( c16) des8.( c16) |
      des4(  f aes) |
      b,( c d) |
      f8( es d4) r |
      <c' g' c>4 r8. g16 a,8. b16 |
      c4 r8. g'16 a8. b16 |
      c4 r8. c16 d8. e16 |
      f4 bes r |
      R2. |
      s2. |
      ges8. f16 ges8. f16 ges8. f16 |
      ges4~ ges16 f es des c bes aes ges |
      ges2 f4 |
      f8. ges16 f8. ges16 f8. aes16 |
      aes2 g!4 |
      g8. aes16 g8. aes16 g8. bes16 |
      bes2 a4 |
      a8 c c4~ c16 bes a bes |
      d8. bes16 a4 r |
      r8. <bes d>16 <g bes>4.. <fis a>16 |
      g8. <bes, d>16 <bes' d>4.. <a c>16 |
      <g bes>8. <d g>16 <bes' g'>4.. <d f>16 |
      <c es>4 <bes d> r |
    }
    
    VII = \relative c'' {
      \voiceTwo
      s4 g2~ |
      g8 r s2 |
      s4 c2 |
    }
    
    %\score {
    %  <<
    %   \new Staff {\RHI}
    %   \new Staff {\VII}
    % >>
    %}
    
    \score {
      \new Staff {
        <<
          \RHI
          \VII
        >>
      }
    }
