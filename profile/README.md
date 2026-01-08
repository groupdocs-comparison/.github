# Document Comparison API & SDKs

[![Product Page](https://img.shields.io/badge/Product%20Page-2865E0?style=for-the-badge&logo=appveyor&logoColor=white)](https://products.groupdocs.com/comparison/family/) 
[![Docs](https://img.shields.io/badge/Docs-2865E0?style=for-the-badge&logo=Hugo&logoColor=white)](https://docs.groupdocs.com/comparison/) 
[![Demos](https://img.shields.io/badge/Demos-2865E0?style=for-the-badge&logo=appveyor&logoColor=white)](https://products.groupdocs.app/comparison/family) 
[![API](https://img.shields.io/badge/API-2865E0?style=for-the-badge&logo=html5&logoColor=white)](https://reference.groupdocs.com/comparison/) 
[![Blog](https://img.shields.io/badge/Blog-2865E0?style=for-the-badge&logo=WordPress&logoColor=white)](https://blog.groupdocs.com/category/comparison/) 
[![Search](https://img.shields.io/badge/Search-2865E0?style=for-the-badge&logo=searchengin&logoColor=white)](https://search.groupdocs.com/) 
[![Support](https://img.shields.io/badge/Support-2865E0?style=for-the-badge&logo=Discourse&logoColor=white)](https://forum.groupdocs.com/c/comparison) 
[![Temp License](https://img.shields.io/badge/Temp%20License-2865E0?style=for-the-badge&logo=rocket&logoColor=white)](https://purchase.groupdocs.com/temporary-license)

**GroupDocs.Comparison** is an enterprise-grade document comparison solution. It allows developers to seamlessly integrate document diffing capabilities into their own applications to detect changes in text, formatting, and document structure across **50+ file formats**.

## 📰 Latest Comparison News & Updates
* Published [GroupDocs.Comparison 25.12](https://www.nuget.org/packages/GroupDocs.Comparison/) — fresh diff engine improvements for faster document compare.
* Updated GitHub examples for .NET — browse the latest samples in the [examples repo](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET).
* Added new blog post — read the latest comparison tips on the [GroupDocs.Comparison blog](https://blog.groupdocs.com/category/comparison/).

## 📂 Supported Platforms & Repository Groups

### 🌐 .NET Document Comparison (C#, ASP.NET, WinForms)
High-performance APIs for the .NET framework and .NET Core.
* **[GroupDocs.Comparison-for-.NET](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET)**: Core engine for C# and VB.NET.
* **[GroupDocs.Comparison-for-.NET-MVC](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET-MVC)**: Web-based comparison UI for ASP.NET MVC.
* **[GroupDocs.Comparison-for-.NET-Web-Forms](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-.NET-Web-Forms)**: Integration samples for Web Forms.

```csharp
// Quick .NET Comparison Example
using (Comparer comparer = new Comparer("source.docx")) {
    comparer.Add("target.docx");
    comparer.Compare("result.docx");
}
```

### ☕ Java Document Comparison (Maven, Spring)
Native Java libraries for cross-platform document processing.
* **[GroupDocs.Comparison-for-Java](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java)**: Standard Java API for file diffing.
* **[GroupDocs.Comparison-for-Java-Spring](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Java-Spring)**: Document comparison for Spring Boot.

```Java
// Quick Java Comparison Example
try (Comparer comparer = new Comparer("source.pdf")) {
    comparer.add("target.pdf");
    comparer.compare("result.pdf");
}
```

### 🟩 Node.js Document Comparison (Node.js via Java)
Fast Node.js integration that wraps the Java engine for cross-platform diffing.
* **[GroupDocs.Comparison-for-Node.js-via-Java](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Node.js-via-Java)**: Runnable samples for comparing Word, PDF, Excel, images, and more from Node.js.

```javascript
// Quick Node.js Comparison Example (path-based)
const groupdocs = require('@groupdocs/groupdocs.comparison');

async function run() {
  const comparer = new groupdocs.Comparer('source.docx');
  comparer.add('target.docx');
  await comparer.compare('result.docx');
}

run().catch(console.error);
```

### 🐍 Python Document Comparison
Fast document diffing scripts using Python via .NET bridge.
* **[GroupDocs.Comparison-for-Python](https://github.com/groupdocs-comparison/GroupDocs.Comparison-for-Python-via-.NET)**: Efficient Python integration for PDF and Word.

```Python
# Quick Python Comparison Example
from groupdocs.comparison import Comparer
with Comparer("source.xlsx") as comparer:
    comparer.add("target.xlsx")
    comparer.compare("result.xlsx")
```

---

## ✅ API Key Features & Benefits
* **Multi-Document Comparison:** Compare more than two files simultaneously to track version history.
* **Detailed Format Support:** Diff PDF, Word (DOCX), Excel (XLSX), PowerPoint (PPTX), and many more.
* **Style & Formatting Detection:** Identify changes in font types, sizes, and styles, not just plain text.
* **Change Management:** Programmatically accept or reject individual detected changes.
* **Metadata Processing:** Preserve or customize metadata in result documents.

## 🆘 Technical Support & Resources
* **Documentation:** Comprehensive [Guides and Tutorials](https://docs.groupdocs.com/comparison/).
* **Support:** Expert help at the [GroupDocs Free Support Forum](https://forum.groupdocs.com/c/comparison).
* **Evaluation:** Download a [Temporary License](https://purchase.groupdocs.com/temporary-license) for full feature testing.