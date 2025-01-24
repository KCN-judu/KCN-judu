# KCN-judu
### A student of industrial design, interested in embedded devlopment and functional programming
- Learning Haskell, MoonBit and Electron.
- Mainly use MoonBit, C++ and JS.

<img src="https://stats.quira.sh/KCN-judu/languages-over-time?theme=dark" height="200px">

# Plans & Current working
## [Chrono (proj)](https://github.com/KCN-judu/Chrono)
I couldn't find a timer application on Nix that met my needs, so I started developing an application called __*Chrono*__ based on __*Electron*__ and __*Node.js*__

![ETC](https://img.shields.io/badge/ETC-25.02-0071C5?style=for-the-badge)
![STATE](https://img.shields.io/badge/STATE-ACTIVE-119F22?style=for-the-badge)

## [Power Macro(proj)](https://github.com/KCN-judu/power-macro)
Due to my unfamiliarity with the C++ addon for __*Node.js*__ and how to use it in __*Electron*__, this project was put on hold for several months.
This project will be reactivated shortly after __*Chrono*__ is completed.

![ETC](https://img.shields.io/badge/ETC-NaN-0071C5?style=for-the-badge)
![STATE](https://img.shields.io/badge/STATE-INACTIVE-FF1121?style=for-the-badge)

## [calculus-numerical(lib)](https://github.com/moonbit-community/calculus-numerical)
This is a calculus numerical solution library written using MoonBit, aiming to fill the gap in scientific computing applications in the MoonBit ecosystem.

![ETC](https://img.shields.io/badge/ETC-LongTerm-0071C5?style=for-the-badge)
![STATE](https://img.shields.io/badge/STATE-ACTIVE-119F22?style=for-the-badge)


# Stats
<img src="https://github-readme-stats.vercel.app/api?username=KCN-judu&show_icons=true&theme=gruvbox&count_private=true" height="150px" alt="logo">

# Workspace Setup
![N100](https://img.shields.io/badge/Intel-N100-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![NixOS](https://img.shields.io/badge/NixOS_25.05-7EBAE4?style=for-the-badge&logo=NixOS&logoColor=5277C3)

# API参考手册

## @KCN-judu/calculus-numerical/basic 基础

### 常量

- **`math_e`**:  
  自然对数的底数  
  $$ e = 2.71828182845904523536028747135 $$

- **`math_log_2_e`**:  
  以 2 为底的对数，输入值为 $$ e $$  
  $$ \log_2(e) = 1.44269504088896340735992468100 $$

- **`math_log_10_e`**:  
  以 10 为底的对数，输入值为 $$ e $$  
  $$ \log_{10}(e) = 0.43429448190325182765112891892 $$

- **`math_sqrt_2`**:  
  2的平方根  
  $$ \sqrt{2} = 1.41421356237309504880168872421 $$

- **`math_sqrt_1_2`**:  
  1/2的平方根  
  $$ \sqrt{\frac{1}{2}} = 0.70710678118654752440084436210 $$

- **`math_sqrt_3`**:  
  3的平方根  
  $$ \sqrt{3} = 1.73205080756887729352744634151 $$

- **`math_pi`**:  
  圆周率  
  $$ \pi = 3.14159265358979323846264338328 $$

- **`math_pi_2`**:  
  圆周率的一半  
  $$ \frac{\pi}{2} = 1.57079632679489661923132169164 $$

- **`math_pi_4`**:  
  圆周率的四分之一  
  $$ \frac{\pi}{4} = 0.78539816339744830961566084582 $$

- **`math_sqrt_pi`**:  
  圆周率的平方根  
  $$ \sqrt{\pi} = 1.77245385090551602729816748334 $$

- **`math_2_sqrt_pi`**:  
  圆周率平方根的倒数乘以 2  
  $$ \frac{2}{\sqrt{\pi}} = 1.12837916709551257389615890312 $$

- **`math_1_pi`**:  
  圆周率的倒数  
  $$ \frac{1}{\pi} = 0.31830988618379067153776752675 $$

- **`math_2_pi`**:  
  圆周率的倒数乘以 2  
  $$ \frac{2}{\pi} = 0.63661977236758134307553505349 $$

- **`math_ln_10`**:  
  10 的自然对数  
  $$ \ln(10) = 2.30258509299404568401799145468 $$

- **`math_ln_2`**:  
  2 的自然对数  
  $$ \ln(2) = 0.69314718055994530941723212146 $$

- **`math_ln_pi`**:  
  圆周率的自然对数  
  $$ \ln(\pi) = 1.14472988584940017414342735135 $$

- **`math_euler`**:  
  欧拉常数，定义为调和级数与自然对数的差的极限  
  \[
  \gamma = \lim_{n \to \infty} \left( \sum_{k=1}^n \frac{1}{k} - \ln(n) \right)
  \]  
  数值约为 $$ 0.57721566490153286060651209008 $$
