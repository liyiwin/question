### 基礎問題
- Kotlin 檔案的副檔名為 ＿？
- `val` 和 `var` 的不同
- `print` 和 `println` 有什麼不同？
- `for (i in 1..10) print(i)` 會印出？
- `for (i in 1 until 10) print(i)` 會印出？
- `for (i in 1..10 step 2) print(i)` 會印出？
- `for (i in 10 downTo 1) print(i)` 會印出？
- Kotlin 中的資料型別有哪些？
- Kotlin 中，如何定義一個不可變的變數？
- `?:` 是什麼運算子？其用途是？
- 請解釋 Kotlin 中的空值安全 (Null Safety) 。
- 請解釋 `when` 用法，與 `switch` 有何不同？

### 進階語法問題
- `typealias NodeSet = Set<Network.Node>` 這段程式要達成的效果是什麼？
- 請解釋 Kotlin 中的擴展函數 (Extension Function)。
- 如何在 Kotlin 中實現單例模式 (Singleton)？
- 請解釋 Kotlin 中的反射 (Reflection)。


### 物件
- `data class` 是什麼？宣告之後在 Kotlin 內產生什麼作用
- `companion object` 是什麼意思？
- `companion object` 和 `object` 的不同？
- 宣告 singleton 時需要使用的關鍵字是什麼？
- Kotlin 中如何定義一個 enum 類型？
- 請解釋 `sealed class` 的功能與使用時機。
- 如何在 Kotlin 中實現介面 (interface)？

### 函數
- scope function 是哪五個
- 使用 `also` 讓兩個變數內容對調
- `tailrec` 關鍵字是什麼意思？在 Kotlin 內如何使用？
- `inline fun` 關鍵字是什麼意思？在 Kotlin 內如何使用？
- 請解釋高階函數 (Higher-Order Function) 的概念。
- `let`, `apply`, `run` 之間有何差異？
- 如何定義一個具有預設參數值的函數？

### lambda
- `var block: (Int) -> String` 宣告內 `block` 的型態是什麼？
- 請解釋 lambda 表達式的基本語法。
- it 在 lambda 中的意義是？

### Collections

- 以下程式碼會印出什麼內容？
```kotlin
val fruits = listOf("banana", "avocado", "apple", "kiwifruit")
fruits
    .filter { it.startsWith("a") }
    .sortedBy { it }
    .map { it.uppercase() }
    .forEach { println(it) }
```
- `listOf(3.14F, 2)` 的型態為？
- `listOf("a", 2)` 的型態為？
- `List` 和 `MutableList` 的不同是？
- 請解釋 mapOf 與 listOf 的差異。
- 如何在 List 中查找特定元素？
- `fold` 和 `reduce` 的功能是？

### Coroutine
- launch 和 async 有什麼不同
- 請解釋 Coroutine 的基本概念。
- `suspend` 關鍵字在 Coroutine 中的作用是？
- `withContext` 的使用場景是？

### 後端開發
- 舉出一個可用 Kotlin 寫後端的框架
- 

