<!-- ============================================================================================================ -->
<!--                         made by               Jan Ritt       -       https://github.com/IxI-Enki             -->
<!-- ============================================================================================================ -->

<div style="page-break-before: always;">

# DSAIUebung-004  --  Predicate Logic Translations

## <div align="center"> Ⅰ ) Translate the following sentences into predicate logic
| $\large{ \qquad natural \space language \space sentenses \qquad \qquad }$ | $\large{ \color{green}{\qquad\qquad pedicate \space logic\qquad}}$ |  
 |:-: |:-:|
 </div>

<div align="left">   
  
  <!--
  > ###### <p align="left">1.</p>
  -->
  | $\small{ Ghosts \space do \space not \space exist. \qquad\qquad\qquad\qquad\qquad\qquad\qquad\quad\space\space }$ | ∀x: isGhost(x) ⇒ ⌐exists(x) |
  |:--------------------:|:---------------------------:|
  <!--
  > ###### <p align="left">2.</p>   
  -->
  | $\small{ Everyone  \space  loves  \space  Helene  \space  Fischer. \qquad\qquad\qquad\qquad\qquad}$ | ∀x: isHuman(x) ⇒ lovesHeleneFischer(x) |
  |:--------------------------------:|:----------------------------------------:|
  <!-- 
  > ###### <p align="left">3.</p>   
  -->
  | $\small{ Someone  \space  actually  \space  likes  \space  asparagus. \qquad\qquad\qquad\qquad\quad}$ | ∃x: isHuman(x) ⇒ likesAspargus(x) |
  |:-----------------------------------:|:-----------------------------------:|
  <!-- 
  > ###### <p align="left">4.</p>   
  -->
  | $\small{ All  \space  things  \space  that  \space breath \space  are \space  alive. \qquad\qquad\qquad\qquad\qquad\space }$ | ∀x: isBreathing(x) ⇒ isAlive(x) |
  |:-----------------------------------:|:---------------------------------:|
  <!--
  > ###### <p align="left">5.</p>   
   -->
  | $\small{ No \space  human \space  being \space  is  \space immortal. \qquad\qquad\qquad\qquad\qquad\quad}$ | ∀x: isHuman(x) ⇒ ⌐isImmortal(x) |
  |:-----------------------------:|:---------------------------------:|
  <!--
  > ###### <p align="left">6.</p>   
  -->
  | $\small{ All \space  that  \space glitters \space  is  \space not  \space gold. \qquad\qquad\qquad\qquad\qquad\qquad\space }$ | ∀x: isGlittering(x) ⇒ ⌐isGold(x) |
  |:--------------------------------:|:----------------------------------:|
  <!--
  > ###### <p align="left">7.</p>   
  -->
  | $\small{ Most  \space Japanese  \space watches  \space are \space  durable \space  and  \space reliable. \qquad\space\space\space}$ | ∃x: isAWatchMadeInJapan(x) ⇒ ¬isDurableAndReliable(x) |
  |:-------------------------------------------------:|:-----------------------------------------:|
  <!--
  > ###### <p align="left">8.</p>   
  -->
  | $\small{ Every  \space  \space human  \space being  \space is  \space afraid  \space of \space  something. \qquad\qquad\space\space}$ | ∀x: isHuman(x) ⇒ isAfraidOfSomething(x) |
  |:-------------------------------------------:|:-----------------------------------------:|
  <!--
  > ###### <p align="left">9.</p>   
  -->
  | $\small{ Some \space  animals \space  hunt \space  everything  \space that \space  flies. \qquad\qquad\quad\space\space\space}$ | ∃x,∀y: isHuntingAnimal(x) ∧ isFlying(y) |
  |:------------------------------------------:|:-----------------------------------------:|
  <!--
  > ###### <p align="left">10.</p>   
  -->
  | $\small{ Not \space  all \space  vegans \space  like  \space all  \space vegetables.\qquad\qquad\qquad\qquad\quad\space\space }$ | ¬∀x: isVegan(x) ⇒ ¬∀y: isAVegetable(y) ∧ likes(x,y) |
  |:-------------------------------------:|:------------------------------------------------------:|
  |                                   or: | ∀x: isVegan(x) ⇒ ∃y: isAVegetable(y) ∧ ¬likes(x,y)  |
  
  </div>
</div>

---

<!-- ============================================================================================================ -->
<!--                         made by               Jan Ritt       -       https://github.com/IxI-Enki             -->
<!-- ============================================================================================================ -->

<!-- fast access to my formating "helper-code" ( 💭 → ✎insert here ): 

// USE THIS TO ENSURE PAGE-BREAKS
<div style="page-break-before: always;">
💭
</div>

// USE THIS TO ALIGN CONTENT
<p align="left"> 💭 </p>
<div align="center"> 💭 </p>

// USE THIS CENTERED TABLE
<div align="center">
  |   |   |   |  
  |:-:|:-:|:-:|  
  |   |   |   |  
</div>

// USE THESE CHARACTERS FOR BEAUTIFUL NOTATIONS
  ✕ ✖ ⅹ ×  ∓ ∗   ∞   ∧ ⋀ ∨ ⋁   ¬   ≡ 
  ⟹   ⇐ ⇒ ⇔   ← → ↔   ⇽ ⇾ ⇿   ⇠ ⇢   ⇦ ⇨
  ∀  ∃ ∄   ∈ ∋  ∊ ∍
  Ⅰ Ⅱ Ⅲ Ⅳ Ⅴ Ⅵ Ⅶ Ⅷ Ⅸ Ⅹ Ⅺ Ⅻ 
  𝐴 𝐵 𝑃 𝑄
  ∘ ∙ • …   ✓ ✔  ✗ ✘  
  ⚐ ⚡
-->
