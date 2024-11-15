<!-- ============================================================================================================ -->
<!--                         made by               Jan Ritt       -       https://github.com/IxI-Enki             -->
<!-- ============================================================================================================ -->

<div style="page-break-before: always;">

# DSAIUebung-004  --  Predicate Logic Translations

## <p align="center"> Ⅰ ) Translate the following sentences into predicate logic</p>  

<div align="left">   

  #### *`natural language sentenses`* | **`pedicate logic`** 
  
  > ###### <p align="left">1.</p>
  | Ghosts do not exist. | ∀x: isGhost(x) ⇒ ⌐exists(x) |
  |:--------------------:|:---------------------------:|
  
  > ###### <p align="left">2.</p>   
  | *Everyone loves Helene Fischer.* | ∀x: isHuman(x) ⇒ lovesHeleneFischer(x) |
  |:--------------------------------:|:----------------------------------------:|
  
  > ###### <p align="left">3.</p>   
  | *Someone actually likes asparagus.* | ∃x: isHuman(x) ⇒ likesAspargus(x) |
  |:-----------------------------------:|:-----------------------------------:|
  
  > ###### <p align="left">4.</p>   
  | *All things that breath are alive.* | ∀x: isBreathing(x) ⇒ isAlive(x) |
  |:-----------------------------------:|:---------------------------------:|
  
  > ###### <p align="left">5.</p>   
  | *No human being is immortal.* | ∀x: isHuman(x) ⇒ ⌐isImmortal(x) |
  |:-----------------------------:|:---------------------------------:|
  
  > ###### <p align="left">6.</p>   
  | *All that glitters is not gold.* | ∀x: isGlittering(x) ⇒ ⌐isGold(x) |
  |:--------------------------------:|:----------------------------------:|
  
  > ###### <p align="left">7.</p>   
  | *Most Japanese watches are durable and reliable.* | ∃x: isAWatchMadeInJapan(x) ⇒ ¬isDurableAndReliable(x) |
  |:-------------------------------------------------:|:------------------------------------------------------:|
  
  > ###### <p align="left">8.</p>   
  | *Every human being is afraid of something.* | ∀x: isHuman(x) ⇒ isAfraidOfSomething(x) |
  |:-------------------------------------------:|:-----------------------------------------:|
  
  > ###### <p align="left">9.</p>   
  | *Some animals hunt everything that flies.* | ∃x,∀y: isHuntingAnimal(x) ∧ isFlying(y) |
  |:------------------------------------------:|:-----------------------------------------:|
  
  > ###### <p align="left">10.</p>   
  | *Not all vegans like all vegetables.* | ¬∀x: isVegan(x) ⇒ ¬∀y: isAVegetable(y) ∧ likes(x,y) |
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
