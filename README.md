##INTRO:
This is a vim keymap file contains mathematic symbols.

    Modified from Charles E.'s math.vim

    Made some effor to reduce typing conflict.

    Superscript : `1 => ¹
    Subscript   : _1 => ₁
    Greek Alphabet: GGA => Α  , GGD => Δ
                    GGa => α  , GGg => γ 
    Fractions   : F1/2 => ½   , F1/3 => ⅓
    Arrows      : <--  => ←   , --v  ==> ↓ , ==>  => ⇒   
                  <--- => ⟵   , --^  ==> ↑ , ===> => ⟹
    Grouping    : ((U  => ⎛   , ]]U  => ⎤  
                  ((M  => ⎜   , ]]M  => ⎥ 
                  ((B  => ⎝   , ]]B  => ⎦ 
                  ((V  => ︵  , ]]V  => ︺
    Misc        : .|3  => ⋮   , INF  => ∞
                  ARC  => ⌒   , ANG1 => ∠
                  DEGC =>  ℃  , DEGF =>  ℉
                  OHM  =>  Ω  , ANGS =>  Å
    Operator    : UU.  =>  ⨃  , UUU  => ∪ , UUN => ∩
                  II1  =>  ∫  , II3  => ∭ , II= => ⨎
                  IO1  =>  ∮  , IO3  => ∰ , IOW => ∳
                  RT2  =>  √  , RT3  => ∛ , RT4 => ∜
                  ''1  =>  ′  , ''2  => ″ , ''3 => ‴
                  PDIF =>  ∂
                  TEF  =>  ∴  , BCS  => ∵
    Relations   : =<=  => ≤   , =>=  => ≥ , =!=  => ≠
                  =<~  => ⪝   , =>~  => ⪞ , =!>  => ≯
                  Oo+  => ⊕   , Oo-  => ⊖
                  OO+  => ⨀   , OOX  => ⨂
    Sets        : SUBO => ⊂   , SUBE => ⊆ , SUBN => ⊄
                  SUPO => ⊃   , SUPX => ⊉
                  LAND => ∧   , LOR  => ∨ , LNOT => ¬
                  LXOR => ⊕
                  SEXT => ∃   , SEXN => ∄ , SALL => ∀
                  NNC  => ℂ   , NNH  => ℍ , NNR  => ℝ
                  NSH  => ℋ   , NSI  => ℑ , NSL  => ℒ
                  SBOT => ⊥   , STOP => ⊤ , SDER => ⊢

**NOTE** view the keymap file (mathematic.vim) for detail mappings.

## HOW TO USE:

Extract to your ~/.vim folder.
Then you can make a mapping to use it.
   
    " use it
    map <leader>km :set keymap=mathematic<CR>
    " stop use it
    map <leader>kn :set keymap=<CR>
    " view it's details, modify it at your convenience.
    map <leader>kvm :sp ~/.vim/keymap/mathematica.vim<CR>

':h keymap' for further details.

Post issues and suggestions at https://github.com/Rykka/mathematic.vim
