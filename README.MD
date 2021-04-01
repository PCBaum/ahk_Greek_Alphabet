## Autohotkey for Greek Letters

This AHK script lets you use a simple version of LaTeX commands in almost every Textfield, that accepts Unicode. 

To write Greek Letters, write Backslash \ followed by the name of the Greek Letter: \alpha → α
To write capitalized Greeek letters, write the Letter Capitalized: \Xi → Ξ

## AHK Installation

  1. Download [Autohotkey](https://www.autohotkey.com/download/) and install it. 
  2. Download the [script Greek_Alphabet.ahk](https://github.com/PCBaum/ahk_Greek_Alphabet/blob/main/Greek_Alphabet.ahk)
   or create a new script with your prefered Name and copy paste the Key Mapping into it.
  3. Put the script into a folder of your choice. 
  4. Start the script Greek_Alphabet.ahk 
  
  Optional: 
  
  5. Compile your Script with rightclick → compile script (shoud be somewhere around the the second row)
  
  6. Put the executable ("YOUR_SCRIPT_NAME".exe) in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.
  
  
# Whithout installing AHK on Windows

  1. Download the compiled [Greek_Alphabet.exe](https://github.com/PCBaum/ahk_Greek_Alphabet/raw/main/Greek_Alphabet.exe) File
  2. Put the script into a folder of your choice.
  3. Start the script Greek_Alphabet.exe
  
  Optional:
  
  4.  Put the executable in your Startup Folder "C:\Users\"USERNAME"\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" to have the script automatically start on Startup.

## Key Mapping 

how this AHK script maps input to output: 
::input::output

```

#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
#Hotstring C * ?
::\alpha::{α}
::\Alpha::{Α}
::\beta::{β}
::\Beta::{Β}
::\gamma::{γ}
::\Gamma::{Γ}
::\delta::{δ}
::\Delta::{Δ}
::\epsilon::{ε}
::\Epsilon::{Ε}
::\zeta::{ζ}
::\Zeta::{Z}
::\eta::{η}
::\Eta::{H}
::\theta::{θ}
::\vtheta::{ϑ}
::\Theta::{Θ}
::\iota::{ι}
::\Iota::{Ι}
::\kappa::{κ}
::\Kappa::{K}
::\lambda::{λ}
::\Lambda::{Λ}
::\mu::{μ}
::\Mu::{M}
::\nu::{ν}
::\Nu::{N}
::\xi::{ξ}
::\Xi::{Ξ}
::\omicron::{ο}
::\Omicron::{Ο}
::\sigma::{σ}
::\endsigma::{ς}
::\csigma::{ς}
::\Sigma::{Σ}
::\pi::{π}
::\Pi::{Π}
::\rho::{ρ}
::\Rho::{Ρ}
::\tau::{τ}
::\Tau::{T}
::\upsylon::{υ}
::\Upsilon::{Y}
::\phi::{φ}
::\Phi::{Φ}
::\chi::{χ}
::\Chi::{X}
::\psi::{ψ}
::\Psi::{Ψ}
::\omega::{ω}
::\Omega::{Ω}
#Hotstring *0 ?0 C0

```

## Credits

Template for AHK Script: was a some time ago and I don't remember. Also, the beginning seems to be standard, and is the only not heavily changed part.

Idea for Github Repository and Template for README.MD [q2apro](https://github.com/q2apro/ahk_greekletters#autohotkey-for-greek-letters)
