## Why is PySpark Called the Python API for Apache Spark?

PySpark is a **Python interface (API)** that allows you to write **Apache Spark** code using **Python**, instead of the native languages like Scala or Java.

---

### 🔍 What Does "Python API" Mean?

- **API** stands for *Application Programming Interface*.
- It's a **set of tools and functions**, i.e., **collection of Python classes and methods** that communicate with the underlying **Spark engine**, which is written in **Scala/Java**.
- PySpark lets you use Python syntax while harnessing Spark's distributed computing power.

---

### 🔧 What Happens Under the Hood?

- When you write code like:

```python
df = spark.read.csv("file.csv")
df.filter(df.age > 30).show()
```
- PySpark translates your Python code into Spark jobs that run on the JVM using Spark’s native engine.

---
### 🧠 In Simple Terms

- Spark is like a **powerful engine** built in Scala.
- PySpark is the **Python steering wheel and dashboard** that lets Python users drive that engine — without needing to know Scala.

---

## ✅ Summary

| Term      | Meaning                                           |
|-----------|---------------------------------------------------|
| PySpark   | Python interface to Apache Spark                  |
| API       | A set of Python-accessible Spark functions        |
| Purpose   | Run big data processing tasks using Python + Spark|

