# 📊 Week 3: Demystifying Data Distribution

Distributions help us understand **how data is spread**, how it behaves, and how to choose the right methods when analyzing or modeling it.

---

## 📈 What Is a Distribution?

A **distribution** shows the frequency or probability of values in a dataset. It answers questions like:

- Are values centered around a point?
- Is the data balanced or skewed?
- Are there extreme values?

---

## 🛎️ The Normal Distribution

The most common and useful distribution is the **normal distribution** (also called the bell curve). It's:

- **Symmetric** around the mean  
- Has most values close to the center  
- Describes natural phenomena like heights, test scores, etc.

---

## ➰ Skewness: Direction of the Curve

**Skewness** tells us if data leans to one side:

- **Zero skewness** → perfectly balanced  
- **Positive skewness** → longer tail to the right  
- **Negative skewness** → longer tail to the left

Skewed data might affect how we summarize or model it, especially when using averages.

---

## 🏔️ Kurtosis: Shape of the Peak

**Kurtosis** measures the "peakedness" of a distribution:

- **Normal kurtosis (0)** → medium peak and tails  
- **High kurtosis (>0)** → sharp peak, heavy tails (more outliers)  
- **Low kurtosis (<0)** → flat peak, light tails (fewer outliers)

It helps us understand the **presence of extreme values**.

---

## 🔎 Why It Matters in Data Science

Understanding distributions is key because:

- Many **machine learning models** assume normality  
- Helps with **choosing the right algorithms**  
- Important for **feature engineering** and **outlier detection**  
- Crucial in **hypothesis testing** and **probability theory**