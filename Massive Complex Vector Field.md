## Proca $\{ B_{\mu} \}$:

$$\mathcal{L}_p = 
-\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu} - m^2 B^{\dagger}_{\mu}B^{\mu}
$$

With $K = d \land B$

$$eom ( \ B_{\mu} \ ) : \ \ \ \ \ \ \partial_{\mu}F^{\mu \nu} = m^2 B^{\nu}  
$$
### Gauge Invariance : 

This breaks Gauge Invariance as: 

$$ \mathcal{L}_p(\{B_\mu\}) \neq \mathcal{L}_p (\{B_\mu+\partial_\mu \Lambda \})

$$


### Noether Current : 

Although Gives the Noether Current $J^{\mu}$ as : 

$$ 
J^{\mu} = K^{\dagger \  \mu \nu} \ \delta B_{\nu} + K^{  \mu \nu} \ \delta B^{\dagger}_{\nu}
$$

### Global $U(1)$ Symmetry : 

Which for $a \ Global \ U(1) \ Symmetry$, gives: 

$$
B_{\mu} \rightarrow B_{\mu} e^{i \ \alpha},  \ \ B^{\dagger}_{\mu} \rightarrow B^{\dagger}_{\mu} e^{-i \ \alpha} \ \ \ \  \implies  \ \ \ \ \delta B_{\mu} = iB_{\mu} \ \ \ and \ \ \ \delta B^{\dagger}_{\mu} = - \ iB^{\dagger}_{\mu}
$$
And the Noether Current takes the form: 
$$ 
J^{\mu}_{_G U(1)} = i \  ( K^{\dagger \  \mu \nu} \  B_{\nu} - K^{  \mu \nu} \  B^{\dagger}_{\nu} )
$$

---

## Stueckleberg $\{ B_{\mu} + \psi \}$:
In order for a massive vector field to be [[#Gauge Invariance :]]  , one requires additional Scalar field with certain properties :
$$\mathcal{L}_s =  
- \ \partial_{\mu}B^{\dagger}_{\nu} \ \partial^{\mu}B^{\nu} 
- \ m^2 B^{\dagger}_{\mu} \ B^{\mu}
+ \ \partial_{\mu}\psi^{\dagger} \ \partial^{\mu}\psi 
- \ m^2 \psi^{\dagger} \psi 

$$

#### New Scalar Field for Gauge Fix

As opposed to previous $Free \ Gauge \ degree$, the invariance of this Lagrangian is more restricted by a $Dynamic \ Gauge \ Freedom$, where :

$$
\mathcal{L}_{s} ( \{B_{\mu} \}\ , \ \{ \psi \} ) = 
\mathcal{L}_{s} ( \ \{B_{\mu} + \partial_{\mu} \Lambda\} \ , \ \{\psi + \frac{1}{m} \Lambda\} \  )
$$ 

## IFF - 

### Dynamic Gauge Freedom :

$$
B_{\mu} \rightarrow  B_{\mu} + \partial_{\mu} \Lambda(x) \ \ \ \ \ and \ \ \ \ \ \psi \rightarrow \psi + \frac{1}{m} \Lambda(x)
$$
With additional $restriction$ on the $gauge \ Function$ as : 

$$
(\partial^{2} - m^2) \ \Lambda = 0
$$
i.e. the gauge function must satisfy $Free \ Klein-Gordon \ Equation$ in order for the whole theory to be **Gauge Invariably Massive** : 


$$
\mathcal{L}_s \rightarrow \bar{\mathcal{L}_s} = 

-\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 ( B^{\dagger}_{\mu} - \frac{1}{m} \partial_{\mu}\psi^{\dagger}) \ ( B^{\mu} - \frac{1}{m} \partial^{\mu}\psi)

$$
$$
- \ (\partial^{\mu}  B_{\mu}^{\dagger} - m\psi^{\dagger})(\partial^{\nu}  B_{\nu} - m\psi)
$$
$$
= \mathcal{L}_s + \partial_{\mu} (B_{\nu}^{\dagger}\partial^{\nu}B^{\mu} - B^{\mu \ \dagger} \partial_{\nu}B^{\nu} - m \psi B^{\mu \dagger} - m\psi^{\dagger} B^{\mu})
$$
$$ = -\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 \ V^{\dagger}_{\mu}V^{\mu}
- (\partial_{\mu} V^{\mu})^{2} 
$$

### Effective Field : 

With this manner, we've considered 

$$V_{\mu} = B_{\mu}- \frac{1}{m}\partial_{\mu}\psi \ \implies \partial_{\mu} V^{\mu} = \partial_{\mu}B^{\mu}-\frac{1}{m} \partial^2 \psi \  \xrightarrow[\text{Transformation}]{\text{Gauge}}$$

$$
\partial_{\mu} V' \ ^{\mu} = \partial_{\mu}B^{\mu} + \partial^2 \Lambda - \frac{1}{m} \partial^2 \psi  - \partial^2 \Lambda = \partial_{\mu} V^{\mu}
$$

In fact the $\{ V_{\mu} \ , \ V^{\dagger}_{\mu} \}$ are **manifestly Gauge Invariant** by the inclusion of [[#New Scalar Field for Gauge Fix]] and choice of definition, which is : 

$$
\bar{\mathcal{L}_s} 
 = -\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 \ V^{\dagger}_{\mu}V^{\mu}
- (\partial_{\mu} V^{\mu})^{2} 
$$ 
Which gives us $\delta \mathcal{\bar{L}_s}$ upon variation .

---

## Coupling with Real Vector Field $\{ A_{\mu} \}$ :

Starting with a **free** Massive Complex vector field and a real vector field,with global $U(1)$ symmetry as [[#Global $U(1)$ Symmetry :]] , we have : 

$$
\mathcal{L}_{0}= \mathcal{\bar{L}_{s}}+ \mathcal{L}_{M} = 
-\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 \ V^{\dagger}_{\mu}V^{\mu}
- (\partial_{\mu} V^{\mu})^{2}  - \frac{1}{4}F^{\mu \nu} F_{\mu \nu}
$$
$$\implies \delta \mathcal{L}_{0}= \delta \mathcal{\bar{L}_{s}}+ \delta \mathcal{L}_M
$$
$$
\delta \mathcal{\bar{L}_s} = 

eom_0[V^{\mu}] \  \delta V^{\dagger}_{\mu} 
+ eom_0 [V^{\dagger}_{\mu}] \ \delta V^{\mu} 
- \partial_{\mu} \ J_0^{\mu}
$$

$$\textbf{with} : \ \ \ \ \ \ \ \ \ \ \ \ eom_0[V^{\mu}] : \ \ \ \ \partial_\nu K^{\mu \nu} + \partial^{\mu}(\partial_{\sigma}V^{\sigma}) - m^2 V^{\mu}$$
$$
J_0^{\mu} = (K^{\mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\sigma}) \ \delta V^{\dagger}_{\nu} + (K^{\dagger \ \mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\dagger \ \sigma}) \ \delta V_{\nu}
$$

$$
\implies J^{\mu}_{_{G} \ 0, \ U(1)} = i \ [(K^{\dagger \ \mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\dagger \ \sigma}) \  V_{\nu} - (K^{\mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\sigma}) \  V^{\dagger}_{\nu} ] = i \ \mathcal{J}^{\mu}
$$

$$\implies \mathcal{L} = \mathcal{L}_{0} + \mathcal{L}_{1} = \ \mathcal{L}_{0} + \ J^{\mu}_{_{G} \ 0, \ U(1)} \ A_{\mu} = -\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 \ V^{\dagger}_{\mu}V^{\mu}
- (\partial_{\mu} V^{\mu})^{2}  $$
$$
- \frac{1}{4}F^{\mu \nu} F_{\mu \nu} + iA_{\mu} \ [(K^{\dagger \ \mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\dagger \ \sigma}) \  V_{\nu} - (K^{\mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\sigma}) \  V^{\dagger}_{\nu} ] 
$$
---
$$
\implies \delta \mathcal{L}_{1} = eom_0[V^{\mu}] \  \delta V^{\dagger}_{\mu} 
+ eom_0 [V^{\dagger}_{\mu}] \ \delta V^{\mu} 
- \partial_{\mu} \ ( J_{0}^{\mu}+ F^{\mu \nu}\delta A_{\nu}) \ 
$$
$$

+ \ (\partial_{\mu}F^{\mu \nu} + i \mathcal{J}^{\nu}) \ \delta A_{\nu} \ - A_{\mu} (\delta \mathcal{J}^{\mu}) 
$$

$$
\textbf{with:} \ \ \ -A_{\mu} \ \delta \mathcal{J}^{\mu} = 
\partial^{\mu} \ (  \ Y_{\mu \nu} \ \delta V^{\dagger \ \nu} - Y^{\dagger}_{\mu \nu} \ \delta V^{\nu} - V_{\nu}A^{\nu} \ \delta V^{\dagger}_{\mu} - V^{\dagger}_{\nu}A^{\nu} \ \delta V_{\mu} \ ) \ - \ \tilde{eom_1}(V^{\dagger \ \mu}) \ \delta V_{\mu} \ + \ 
\tilde{eom_1}(V^{ \mu}) \ \delta V^{\dagger}_{\mu}
$$
$$
\textbf{where :} \ \ \ \ Y_{\nu \mu} = V_{[\nu}A_{\mu ] }, \ \ Y^{\dagger}_{\nu \mu} = V^{\dagger}_{[\nu}A_{\mu ] } \ \ \implies \ \ Y_{\mu \nu} = - Y_{\nu \mu}
$$
$$
\tilde{eom_1}(V^{\mu}) \ : \ \ \ \ \ \ \ \ \ A_{\nu} K^{\mu \nu} +A^{\mu} \ (\partial_{\sigma}V^{\sigma}) + \partial_{\nu} \ Y^{\mu \nu} - \partial^{\mu} \ (V_{\sigma} A^{\sigma})

$$
$$
The \ New \ Noether \ Current : \ \ \ \ \mathcal{J}^{1}_{\mu} = Y_{\mu \nu} \ \delta V^{\dagger \ \nu} - Y^{\dagger}_{\mu \nu} \ \delta V^{\nu} - V_{\nu}A^{\nu} \ \delta V^{\dagger}_{\mu} - V^{\dagger}_{\nu}A^{\nu} \ \delta V_{\mu}
$$
$$\implies  J^{\mu}_{_{G} \ 1, \ U(1)} = 2i \ (V^{\dagger}_{\nu} V^{\nu} A^{\mu} - A_{\nu}V^{\nu}V^{\mu}) = 2i \ \mathcal{J}^{\mu}_{2}
$$

---

The further term to be added in the Lagrangian is $$\mathcal{L}_{2} = \frac{1}{2} \ ( \ 2i \mathcal{J}^{\mu}_{2} A_{\mu} \ ) = i A_{\mu}\mathcal{J}_{2}^{\mu} \ \ \  such \ that \ \frac{\delta}{\delta A_{\mu}}\int d^{4}x \mathcal{L}_{2} = \mathcal{J}^{\mu}_{2}$$

Furthermore, we notice the Seagull vertex $(V^{\mu}V_{\mu} A^{\mu}A_{\mu} \ \equiv \ V^{2} A^{2})$ term in the interaction, as : 

$$\mathcal{L}_{2}= iA_{\mu}(V^{\dagger}_{\nu} V^{\nu} A^{\mu} - A_{\nu}V^{\nu}V^{\mu}) = i \ (V^{2}A^{2} - (A.V)^{2})$$
The Final Lagrangian therefore becomes :


$$
\mathcal{L} = \mathcal{L}_{0}+\mathcal{L}_{1} + \mathcal{L}_{2} = \mathcal{\bar{L}_{s}}+ \mathcal{L}_{M} + \mathcal{L}_{1} + \mathcal{L}_{2}
$$
$$
\implies \mathcal{L} = -\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu}
- m^2 \ V^{\dagger}_{\mu}V^{\mu}
- (\partial_{\mu} V^{\mu})^{2}  - \frac{1}{4}F^{\mu \nu} F_{\mu \nu}
$$
$$
+ \ iA_{\mu} \ [(K^{\dagger \ \mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\dagger \ \sigma}) \  V_{\nu} - (K^{\mu \nu} + \eta^{\mu \nu} \partial_{\sigma}V^{\sigma}) \  V^{\dagger}_{\nu} ] + i \ (V^{2}A^{2} - (A.V)^{2}) 
	$$ 

## First order Effective Stueckleberg Theory: 

The $V_{\mu}$ previously considered is manifestly gauge invariant, nevertheless it is not the Vector field, the theory was supposedly built for, which is $B_{\mu}$ ; rather, $V_{\mu}$ is $\textbf{gauge corrected}$ $B_{\mu}$ which means, the Gauge-and-Lorentz invariance of $V_{\mu}$-theory indicates its effective physicality, beyond the picture of $B_{\mu}$ . Therefore, $V_{\mu}$ here is considered as the $\textbf{Effective Vector Field}$, which is massive and gauge-independent. 

The First order Lagrangian of Effective Stueckleberg Field $V_{\mu}$ is : 

$$
\mathcal{\bar{L}}_{s} = \Gamma^{\mu \nu} (\partial_{\mu}V^{\dagger}_{\nu} - \partial_{\nu}V^{\dagger}_{\mu}) + 
\Gamma^{\dagger \ \mu \nu} (\partial_{\mu}V^{}_{\nu} - \partial_{\nu}V^{}_{\mu}) + \tilde{\Gamma}(\partial^{\mu}V^{\dagger}_{\mu}) + \tilde{\Gamma^{\dagger}}(\partial^{\nu}V^{}_{\nu}) \ 
$$
$$
- \ (m^{2}V^{\dagger}_{\mu}V^{\mu} + a\Gamma^{\mu \nu} \Gamma_{\mu \nu}^{\dagger} + b\tilde{\Gamma^{\dagger}}\tilde{\Gamma})
$$
Which upon variation of the Lagrangian, w.r.t. $\Gamma^{\mu \nu}s$ and $\tilde{\Gamma }s$, we obtain: 

$$
\frac{1}{a}K^{\mu \nu} = \Gamma^{\mu \nu}  \ \ \ \ \ \ and \ \ \ \ \ \frac{1}{b}(\partial_{\sigma}V^{\sigma}) = \tilde{\Gamma}
$$
which when substituted back, we get : $a = -2 = b$

### Coupling with $A_{\mu}$ : 

Under the first order framework, the free theory is as : 

$$\mathcal{L}_{0}= \mathcal{\bar{L}}_{s} + \mathcal{L}_{M}=\mathcal{\bar{L}}_{s} = \Gamma^{\mu \nu} (\partial_{\mu}V^{\dagger}_{\nu} - \partial_{\nu}V^{\dagger}_{\mu}) + 
\Gamma^{\dagger \ \mu \nu} (\partial_{\mu}V^{}_{\nu} - \partial_{\nu}V^{}_{\mu}) + \tilde{\Gamma}(\partial^{\mu}V^{\dagger}_{\mu}) + \tilde{\Gamma^{\dagger}}(\partial^{\nu}V^{}_{\nu}) \  + \Pi_{\mu \nu}F^{\mu \nu}$$

$$
- \ (m^{2}V^{\dagger}_{\mu}V^{\mu} -2\Gamma^{\mu \nu} \Gamma_{\mu \nu}^{\dagger} -2 \tilde{\Gamma^{\dagger}}\tilde{\Gamma} + \Pi_{\mu \nu}\Pi^{\mu \nu})
$$