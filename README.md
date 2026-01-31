# **UCS – Universal Converter Switch (Java Desktop Application)**

## **Project Overview**
**UCS (Universal Converter Switch)** is a **comprehensive, user-friendly desktop application** developed in Java that allows users to perform real-time conversions across multiple measurement and data types. The application is designed for simplicity, accuracy, and efficiency, catering to students, professionals, engineers, and everyday users who need quick and reliable conversion tools.

## **Key Features**

### **1. Multi-Category Conversion**
UCS supports conversion across **five core categories**:
- **Mass** (e.g., kilograms, pounds, ounces, grams)
- **Length** (e.g., meters, feet, inches, miles, kilometers)
- **Data Size** (e.g., bytes, kilobytes, megabytes, gigabytes, terabytes)
- **Area** (e.g., square meters, square feet, acres, hectares)
- **Currency** (real-time or offline with update capability)

### **2. User-Friendly Interface**
- **Tabbed or dropdown selection** for conversion categories
- **Clean input/output panels** with labeled fields
- **Instant conversion** as the user types
- **Swap button** to reverse source and target units
- **History panel** to review recent conversions

### **3. Currency Conversion with Live Updates**
- **Integration with a financial API** (e.g., Open Exchange Rates, Fixer.io)
- **Offline mode** with cached exchange rates
- **Manual update option** for latest rates
- **Support for 150+ global currencies**

### **4. Advanced Functionality**
- **Custom unit support** – users can define their own conversion ratios
- **Favorites/Recent** – quick access to frequently used conversions
- **Batch conversion** – convert multiple values at once
- **Export results** to CSV or text file
- **Copy to clipboard** with one click

### **5. Settings & Preferences**
- **Theme selection** (Light/Dark mode)
- **Decimal precision** control (2–10 decimal places)
- **Language/localization** support (optional)
- **Update currency rates automatically** on launch

## **Technical Specifications**

### **Programming Language & Framework**
- **Java SE 11+**
- **Java Swing or JavaFX** for GUI
- **Maven/Gradle** for dependency management
- **SQLite** for storing conversion history and user preferences (optional)

### **Architecture**
- **Model-View-Controller (MVC)** pattern
- **Modular design** – each converter is a separate module
- **Service layer** for API integration and data handling

### **External APIs & Libraries**
- **Currency conversion API** (e.g., exchangerate-api.com)
- **JUnit** for unit testing
- **Log4j** for logging
- **Google Gson/Jackson** for JSON parsing (currency data)

## **Target Users**
- **Students & Educators** – for academic and homework assistance
- **Engineers & Scientists** – for technical calculations
- **Financial Professionals** – for currency conversions
- **General Public** – for everyday measurement needs

## **Project Goals**
1. Provide a **fast, accurate, and offline-capable** conversion tool.
2. Deliver an **intuitive UI** with no learning curve.
3. Ensure **reliability** with error handling and validation.
4. Support **extensibility** for adding new converters in the future.

## **Future Enhancements**
- **Temperature, Time, and Speed** converters
- **Voice input** support
- **Mobile app version** (Android/iOS)
- **Plugin system** for third-party converters
- **Cloud sync** of user preferences and history

