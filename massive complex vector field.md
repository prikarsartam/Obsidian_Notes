## Proca $\{ B_{\mu} \}$:

$$\mathcal{L}_p = 
-\frac{1}{2} K^{\dagger}_{\mu \nu} \ K^{\mu \nu} - m^2 B^{\dagger}_{\mu}B^{\mu}
$$

With $K = d \land B$

$$EOM \ ( \ B_{\mu} \ ) : \ \ \ \ \ \ \partial_{\mu}F^{\mu \nu} = m^2 B^{\nu}  
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
\delta B_{\mu} = iB_{\mu} \ \ \ and \ \ \ \delta B^{\dagger}_{\mu} = - \ iB^{\dagger}_{\mu}
$$
And the Noether Current takes the form: 
$$ 
J^{\mu}_{_G U(1)} = i \  ( K^{\dagger \  \mu \nu} \  B_{\nu} - K^{  \mu \nu} \  B^{\dagger}_{\nu} )
$$


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