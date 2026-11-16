## <span style="background-color: rgba(213, 142, 173, 0.30);">Число e как предел числовой последовательности</span>

#Число_е_как_предел_числовой_последовательности

### Число $e$ как предел числовой последовательности

---

Утверждение:

$$
\exists\lim_{n \to \infty} \left(1+\frac{1}{n}\right)^n
$$

---

Доказательство:

$$
x_n=\left(1+\frac{1}{n}\right)^n=\sum_{k=0}^{n}C_n^ka^{m-k}=
$$

$$
= C_n^0\left(\frac{1}{n}\right)^n+\dots+C_n^{n-3}\left(\frac{1}{n}\right)^3+C_n^{n-2}\left(\frac{1}{n}\right)^2+C_n^{n-1}\left(\frac{1}{n}\right)^1+C_n^n\left(\frac{1}{n}\right)^0=
$$

---

$$
C_n^0=C_n^n=1
$$

$$
C_n^{n-3}=\frac{n!}{(n-3)!(n-n+3)!}=\frac{n(n-1)(n-2)(n-3)!}{(n-3)!3!}=\frac{n(n-1)(n-2)}{3!}
$$

$$
C_n^{n-2}=\frac{n!}{(n-2)!(n-n+2)!}=\frac{n(n-1)(n-2)!}{(n-2)!2!}=\frac{n(n-1)}{2!}
$$

$$
C_n^{n-1}=\frac{n!}{(n-1)!(n-n+1)!}=\frac{n(n-1)!}{(n-1)!1!}=\frac{n}{1!}=n
$$

---

$$
=1\left(\frac{1}{n}\right)^n+\dots+\frac{n(n-1)(n-2)}{3!}\left(\frac{1}{n}\right)^{3}+\frac{n(n-1)}{2!}\left(\frac{1}{n}\right)^{2}+n\frac{1}{n}+1=
$$

$$
=\left(\frac{1}{n}\right)^n+\dots+\frac{(n-1)(n-2)}{3!}\left(\frac{1}{n}\right)^{2}+\frac{(n-1)}{2!}\left(\frac{1}{n}\right)+2=
$$

$$
=\left(\frac{1}{n}\right)^n+\dots+\frac{1}{3!}\left(1+\frac{1}{n}\right)\left(1+\frac{2}{n}\right)+\frac{1}{2!}\left(1+\frac{1}{n}\right)+2=
$$

---

Запишем сумму $\underleftarrow{\text{с право на лево}}$:

---

$$
=2+\frac{1}{2!}\left(1+\frac{1}{n}\right)+\frac{1}{3!}\left(1+\frac{1}{n}\right)\left(1+\frac{2}{n}\right)+\dots+\\+\frac{1}{n!}\left(1+\frac{1}{n}\right)\left(1+\frac{2}{n}\right)\left(1+\frac{3}{n}\right)*\dots*\left(1+\frac{n-1}{n}\right)\le
$$

---

Заметим:

$$
\left(1+\frac{1}{n}\right)<1
$$

$$
\left(1+\frac{1}{n}\right)\left(1+\frac{2}{n}\right)<1
$$

---

$$
\le 2+\frac{1}{2!}+\frac{1}{3!}+\dots+\frac{1}{n!}\le
$$

$$
\le2+\frac{1}{2^1}+\frac{1}{2^2}+\dots+\frac{1}{2^{n-1}}=
$$

---

Геометрическая прогрессия:

$$
S_n=\frac{b_1(1-q^n)}{1-q}
$$

---

$$
= 2+\frac{\frac{1}{2}\left(1-\left(\frac{1}{2}\right)^{n-1}\right)}{1-\frac{1}{2}}=3+\left(\frac{1}{2}\right)^{n-1}<3
$$

---

Таким образом:

$$
\exists\lim_{n \to \infty} x_n=e
$$