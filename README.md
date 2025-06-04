# Dead Clock ⏳☠️

**A Java mortality countdown** using `Locale`, `LocalDate`, and actuarial data to estimate your remaining minutes of life—personalized by age, habits, and location.

## 🔮 Core Features
- **Precision Time Calculation**  
  Uses `java.time.LocalDate` for birthdate parsing and `LocalTime` for minute-by-minute countdowns
- **Locale-Aware Life Expectancy**  
  Leverages `java.util.Locale` to adjust estimates based on regional health data
- **Customizable Mortality Factors**  
  - Smoking status (`boolean`)  
  - Exercise frequency (`enum`)  
  - Family health history  
  - BMI analysis

## 📦 Tech Stack
```java
import java.time.{LocalDate, LocalTime, Period};
import java.util.Locale;
import java.text.NumberFormat;
import lombok.*;
