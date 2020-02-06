---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# test_md2html

## "##"

### "###"

#### "####"

##### "#####"

###### "######"

####### "#######"

| Left align | Right align | Center align |
| :--------- | ----------: | :----------: |
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |

$a = {1, 2, 3}$

$a = \{1, 2, 3\}$

$a = \\{1, 2, 3\\}$

$\left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$

```math
\left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```


<br/>

\\[
\begin{xy}
*[gray] \xymatrix@!R=1ex@!C=2ex  {
&{召喚}\ar@/^/[ddr]^{}\\\
& \txt{} & \\\
{回復}\ar@/^/[uur]^{} & & {反射}\ar@<-0.8ex>@/^/[ll]_{}\\\
}
\end{xy}
\\]

<br/>

\xy *+<1.5pt>[F**:white]++[F**:red] \txt{text with background} 
,+!D+/d1pc/,*++[F**:black][white] \txt\bf{bold white on black}\endxy

$ \begin{xy}*++[]{\text{\frm<6pt>{\*}}} \*\frm<1pt>{\*}, \end{xy}$

\\[ \begin{xy}+/d3em/\*++[]{\text{\frm<6pt>{\*}}} \*\frm<6pt>{\*}, \end{xy}\\]

$*+<1.5pt>[F\*\*:white]++[F\*\*:red]$

\\[
\begin{xy}
*+<1.5pt>[F\*\*:white]++[F\*\*:red] \xymatrix@!R=1ex@!C=2ex  {
&{召喚}\ar@/^/[ddr]^{}\\\
& \txt{} & \\\
{回復}\ar@/^/[uur]^{} & & {反射}\ar@<-0.8ex>@/^/[ll]_{}\\\
}
\end{xy}
\\]


\\[
\begin{xy}
,+!D+/d1pc/,*++[F\*\*:black]+<-1.5pt>[F\*\*:gray][thistle] \xymatrix@!R=1ex@!C=2ex  {
&{召喚}\ar@/^/[ddr]^{}\\\
& \txt{} & \\\
{回復}\ar@/^/[uur]^{} & & {反射}\ar@<-0.8ex>@/^/[ll]_{}\\\
}
\end{xy}
\\]


### TeX-like Math Syntax
I can also render TeX-like math syntaxes, if you allow me to.[^math] I can do inline math like this: \\( 1 + 1 \\) or this (in MathML): <math><mn>1</mn><mo>+</mo><mn>1</mn></math>, and block math:

\\[
    A^T_S = B
\\]


\\\[
    A^T_S = B
\\\]

or (in MathML)

<math display="block">
    <msubsup><mi>A</mi> <mi>S</mi> <mi>T</mi></msubsup>
    <mo>=</mo>
    <mi>B</mi>
</math>


\[
  \frac{\pi}{2} =
  \left( \int_{0}^{\infty} \frac{\sin x}{\sqrt{x}} dx \right)^2 =
  \sum_{k=0}^{\infty} \frac{(2k)!}{2^{2k}(k!)^2} \frac{1}{2k+1} =
  \prod_{k=1}^{\infty} \frac{4k^2}{4k^2 - 1}
\]


\\[
  \frac{\pi}{2} =
  \left( \int_{0}^{\infty} \frac{\sin x}{\sqrt{x}} dx \right)^2 =
  \sum_{k=0}^{\infty} \frac{(2k)!}{2^{2k}(k!)^2} \frac{1}{2k+1} =
  \prod_{k=1}^{\infty} \frac{4k^2}{4k^2 - 1}
\\]

\\[
\alpha =
\begin{pmatrix}
a_{11} & a_{12} & \ldots & a_{1n} \\\
a_{21} & a_{22} & \ldots & a_{2n} \\\
\vdots & \vdots & \ddots & \vdots \\\
a_{n1} & a_{n2} & \ldots & a_{nn}
\end{pmatrix}
\\]

\\[
\require{AMScd}
\begin{CD}
A\times A\times A  @\>\>\>  A\times A \\\
@VVV                     @VVV \\\
A\times A          @\>\>\>  A
\end{CD}
\\]

\\[ \␣ \quad \qquad \, \: \; \! \\]
小さいスペース
大きいスペース \quad の 2 倍 \quad の 3/18 倍 \quad の 4/18 倍 \quad の 5/18 倍 \quad の −3/18 倍(負のスペース)
ギリシア文字(小文字)
    
ギリシア文字(大文字)
\\[ \alpha \beta \gamma \delta \epsilon\varepsilon \\]
α β γ δ ε ε
\\[ \zeta \eta \theta \vartheta \iota \kappa \\]
ζ η θ θ ι κ
\\[ \lambda \mu \nu \xi \o \pi \\]
λ μ ν ξ o π
\\[ \varpi \rho \varrho \sigma \varsigma \tau \\]
π ρ ρ σ ς τ
\\[ \upsilon \phi \varphi \chi \psi \omega \\]
υ φ φ χ ψ ω
\\[ \Gamma \varGamma \Delta \varDelata \Theta \varTheta \\]
 Γ Γ ∆ ∆ Θ Θ
\\[ \Lambda \varLambda \Xi \varXi \Pi \varPi \\]
Λ Λ Ξ Ξ Π Π
\\[ \Sigma \varSigma \Upsilon \varUpsilon \Phi \varPhi \\]
Σ Σ Υ Υ Φ Φ
\\[ \Psi \varPsi \Omega \varOmega \\]
 Ψ Ψ Ω Ω
   
括弧類
\\[ (x) [x] \{x\} \langle x \rangle \lfloor x \rfloor \lceil x \rceil \\]
(x) [x] {x} ⟨x⟩ ⌊x⌋ ⌈x⌉
\\[ |x| \|x\| / \backslash \\]
|x| ∥x∥ / \
 
13
二項演算子
\\[ + - \pm \mp \times \div \\]
+ − ± ∓ × ÷
\\[ \ast \star \cdot \bullet \circ \bigcirc \\]
∗ ⋆ · • ◦ ⃝
\\[ \setminus \wr \cap \cup \sqcap \sqcup \\]
       \ ≀ ∩ ∪ ⊓ ⊔
\\[ \wedge \vee \oplus \ominus \otimes \oslash \\]
       ∧ ∨ ⊕ ⊖ ⊗ ⊘
\\[ \odot \dagger \ddagger \amalg \\]
       ⊙ † ‡ ⨿
              
     関係演算子
\\[ = \neq \doteq \doteqdot \equiv \sim \backsim \simeq \backsimeq \eqsim \approx \approxeq \\]
= ̸= =.  ≡ ∼ 􏰯 ≃ 􏰰 􏰍 ≈ 􏰐
\\[ \cong \propto \varpropto \perp \mid \shortmid \parallel \shortparallel \therefore \because \risingdotseq \fallingdotseq \\]
             ∼= ∝ ∝ ⊥ | 􏰎 ∥ 􏰏 ∴ ∵ 􏰧 􏰨
\\[ < > \ll \gg \lll \ggg \le, \leq \ge, \geq \leqq \geqq \leqslant \geqslant \\]
             < > ≪ ≫ ≪ ≫ ≤ ≥ 􏰤 􏰩 􏰥 􏰪
\\[ \lesssim \gtrsim \subset \supset \subseteq \supseteq \subseteqq \supseteqq \in \ni \notin \backepsilon \\]
             􏰣 􏰡 ⊂ ⊃ ⊆ ⊇ 􏰭 􏰮 ∈ ∋ ∈/ 􏰔
                         
    ※ \not で斜線を重ねることができます。例:\not\equiv ⇒ ̸≡ 雑記号
   
\\[ \emptyset \varnothing \infty \aleph \complement \partial \digamma \hbar \hslash \imath \jmath \\]
            ∅ ∅ ∞ א 􏰱 ∂ 􏰑 􏰓 􏰒 ı ȷ
\\[ \Bbbk \varkappa \ell \Re \Im \mho \eth \prime \backprime \surd \nabla \\]
            k κ l R I  ð ′  √ ∇
\\[ \triangle \square \blacksquare \bigstar \spadesuit \heartsuit \diamondsuit \clubsuit \angle \measuredangle \sphericalangle \\]
            △  􏰖 ⋆ ♠ ♡ ♢ ♣ ∠ 􏰫 􏰬
\\[ \top \bot \diagup \diagdown \forall \exists \nexists \neg, \lnot \sharp \flat \natural \\]
            ⊤ ⊥ 􏰉 􏰊 ∀ ∃ 􏰋 ¬ ♯ ♭ ♮

関数記号
\\[ \sin \cos \tan \cot \sec \csc \arcsin \arccos \arctan \\]
          sin cos tan cot sec csc arcsin arccos arctan
\\[ \sinh \cosh \tanh \coth \exp \log \ln \lg \arg \\]
          sinh cosh tanh coth exp log ln lg arg
\\[ \Pr \det \hom \ker \dim \deg \gcd \bmod \pmod{n} \\]
          Pr det hom ker dim deg gcd mod (mod n)
\\[ \lim \min \max \inf \sup \liminf \limsup \\]
          lim min max inf sup lim inf lim sup
                    大きな記号
   
∑⊔∫ ∏∧􏰄
⨿ ∨ ∫∫ ∩          ⊕          ∫∫∫   ∪ ⊗ ∫∫∫∫
\\[ \sum \prod \coprod \bigcap \bigcup \biguplus \bigsqcup \bigwedge \bigvee \bigoplus \bigotimes \bigodot \int \oint \iint \iiint \iiiint \idotsint \\]
                      ⊎           ⊙           ∫ ···∫ ※ _{}^{} で下限や上限を付けることができます。
     矢印
\\[ \rightarrow, \to \leftarrow, \gets \longrightarrow \longleftarrow \leftrightarrow \longleftrightarrow \mapsto \longmapsto \hookrightarrow \hookleftarrow \rightleftarrows \leftrightarrows \rightrightarrows \leftleftarrows \\]
               →
← −→ ←− ↔ ←→ 􏰈→ 􏰈−→ 􏰂→ ←􏰃 􏰠 􏰟 ⇒ ⇔
\\[ \uparrow \downarrow \updownarrow \upuparrows \downdownarrows \nearrow \searrow \nwarrow \swarrow \Rightarrow \Leftarrow \Longrightarrow \Longleftarrow \Leftrightarrow \\]
               ↑ ↓ ↕ 􏰙 􏰚 ↗ ↘ ↖ ↙ ⇒ ⇐ =⇒ ⇐= ⇔
\\[ \Longleftrightarrow \Uparrow \Downarrow \Updownarrow \rightharpoonup \rightharpoondown \leftharpoonup \leftharpoondown \rightleftharpoons \leftrightharpoons \upharpoonleft \upharpoonright \downharpoonleft \downharpoonright \\]
               ⇐⇒ ⇑ ⇓ ⇕ ⇀ ⇁ ↼ ↽ 􏰗 􏰘 􏰝
􏰛
􏰞
􏰜
                            
   15

上下に付ける記号
\\[ \vec{x} \bar{x} \tilde{x} \breve{x} \hat{x} \check{x} \\]
⃗x x ̄ x ̃ x ̆ xˆ xˇ
\\[ \acute{x} \grave{x} \dot{x} \ddot{x} \dddot{x} \ddddot{x} \\]
x ́
x`
x ̇
x ̈ ...
x
....
x
\\[ \overrightarrow{xyz} \overleftarrow{xyz} \overline{xyz} \underline{xyz} \widetilde{xyz} \widehat{xyz} \\]
−→
xyz
←−
xyz xyz xyz x􏰇yz x􏰆yz


HTML

<table>
    <tr>
        <td>Foo1</td>
        <td>Foo2</td>
    </tr>
    <tr>
        <td>Foo3</td>
        <td>Foo4</td>
    </tr>
</table>

<details><summary>summary</summary>details</details>


<blockquote class="twitter-tweet"><a href="https://twitter.com/nenten/status/1204111092223336448" /></blockquote>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">やさしいものをみて心をたいせつにしようね</p>&mdash; ねんてんくん (@nenten) <a href="https://twitter.com/nenten/status/1204111092223336448?ref_src=twsrc%5Etfw">December 9, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

