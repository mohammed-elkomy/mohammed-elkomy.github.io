Last week, I attended a webinar where a presenter, a personal coach, tried to use mathematical analogies involving physical quantities raised to powers. 
While the intention was creative, it highlighted a widespread misunderstanding about using powers in physics equations.

That equation he presented, with my all due respect, was something like:
$$Impact = (Experience+ BlaBla_1*BlaBla_2) ^ (Compassion)$$

---

### 🚫 The Problem with Units in Exponents  
Consider the exponential decay formula:  
$$ N(t) = N_0 e^{-\lambda t} $$  
Here, the exponent $$-\lambda t$$ *must* be dimensionless. If $$\lambda$$ (decay constant) has units of $$[T^{-1}]$$ and $$t$$ is time $$[T]$$, their product $$\lambda t$$ cancels units, leaving a pure number.  

Now imagine if $$\lambda t$$ had units, say $$[T]$$. The Taylor expansion of $$e^{-\lambda t}$$ would become:  
$$ 1 - \lambda t + \frac{(\lambda t)^2}{2!} - \frac{(\lambda t)^3}{3!} + \dots $$  
Each term here would have *different dimensions* (e.g., $$1$$, $$[T]$$, $$[T^2]$$), making the sum meaningless. **You can’t add meters to meters-squared!**  

---

### 🔍 Why Dimensionless Exponents Are Non-Negotiable  
#### 1. **Mathematical Consistency**  
   Functions like $$e^x$$, $$\sin(x)$$, and $$\log(x)$$ are defined for *pure numbers*. For example, the series expansion of $$e^x = 1 + x + \frac{x^2}{2!} + \dots$$ only works if $$x$$ is dimensionless.  

#### 2. **Dimensional Homogeneity**  
   All terms in a physics equation must share the same dimensions. Take the kinematic equation:  
   $$ s = ut + \frac{1}{2}at^2 $$  
   The exponent $$2$$ in $$t^2$$ is dimensionless, but $$t^2$$ itself has units $$[T^2]$$, ensuring consistency with the other terms.  

#### 3. **Real-World Ratios**  
   Even in "dimensional" powers, exponents are hidden ratios. For example, the Arrhenius equation in chemistry:  
   $$ k = A e^{-E_a / (RT)} $$  
   Here, $$E_a / (RT)$$ is unitless because $$E_a$$ (energy) and $$RT$$ (energy) share the same dimensions.  

---

### 🌐 Examples of Dimensionless Powers in Action  
- **Radioactive decay**: $$ N(t) = N_0 \left(\frac{1}{2}\right)^{t / t_{1/2}} $$  
  The exponent $$t / t_{1/2}$$ is a ratio of two times, making it unitless.  
- **Stokes' law drag force**: $$ F = 6\pi \eta r v $$  
  If rewritten as $$ F \propto v^1 $$, the exponent $$1$$ is dimensionless.  

---

### 🔑 The Bottom Line  
Using dimensional quantities in exponents isn’t just “technically wrong”-it breaks the foundational logic of physics.
Units ensure equations describe reality coherently, and dimensionless exponents are a non-negotiable part of that framework.
Next time you see someone write $$x^{3\,\text{kg}}$$, gently remind them: **exponents are pure numbers, not playgrounds for units** 😉.  

Stay curious, and keep those equations dimensionally consistent! 🌟
