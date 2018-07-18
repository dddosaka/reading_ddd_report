用語「コンテキスト」に関する記述の抜粋

14章

p.340

> 明示的に考える機会はあまりないのだが、モデルに対する最も根本的な要件は、内部で一貫していることだ。これは、用語の意味が常に同じであることであり、矛盾したルールが含まれていないことでもある。各用語の意味が明瞭で矛盾したルールがないという、モデルの内部におけるこうした一貫性は、 **統一性** (unification) と呼ばれる。あるモデルは、論理的に一貫していなければ意味がない。


p.341

> 境界づけられたコンテキストによって、各モデルを適用できる範囲が定義され、（略）


p.344

> あるモデルが適用されるのは、ある **コンテキスト** の中においてである。そのコンテキストというのは、コードのある部分であるかもしれないし、ある特定のチームによる作業のことかもしれない。（略）モデルのコンテキストとは、モデル内の用語が特定の意味を持つと言えるようにするために適用しなければならない、あらゆる条件の集合である。
（略）
境界づけられたコンテキストは、特定のモデルが適用できる範囲を制限する。（略）

p.345

> コラムー境界づけられたコンテキストはモジュールではない
>
> この問題は混同されることもあるが、動機が異なる別々のパターンなのだ。確かに、２つのオブジェクトの集合が別々のモデルを構成していると認識される場合、そうしたオブジェクトはほとんど常に別個の **モジュール** に置かれることになる。そうすることで、別々の名前空間（異なる **コンテキスト** には不可欠）と何らかの境界が与えられる。
しかし、 **モジュール** は１つのモデルの中で複数の要素を構成するものでもあり、別々の **コンテキスト** に対して、必ずしも意図を伝えるものではない。  **境界付けられたコンテキスト** の中で **モジュール** が個別の名前空間を作成することにより、実は、偶発的に発生するモデルの断片化が見つけにくくなっていうるのだ。


原著
p.336

> The issues are confused sometimes, but these are different patterns with diffirent motivations. 
True, when two sets of objects are recognized as making up defferent models, they are almost always placed in separate **modules** . Doing so does provide different name spaces (essential for different **CONTEXTS** ) and some demarcation.
But **MODULES** also organize the elements within one model; they don't necessarily communicate an intention to separate **CONTEXTS** . The separate name spaces that **MODULES** create *witbin* a **BOUNDED CONTEXT** actually make it harder to spot accidental model fragmentation.

