# Bernoulli vs Binomial Distributions 🎯

This simple Python project visualizes the difference between the **Bernoulli** and **Binomial** probability distributions using `matplotlib` and `scipy`.

## 📊 What's Inside?

- **Bernoulli Distribution**: A single trial with two outcomes (0 or 1).
- **Binomial Distribution**: The probability of `k` successes in `n` independent Bernoulli trials.

This project helps illustrate that the Bernoulli distribution is a special case of the Binomial distribution when `n = 1`.

## 📌 Formula Recap

### Bernoulli:
P(X = x) = p^x * (1 - p)^(1 - x), where x ∈ {0, 1}

### Binomial:
P(X = k) = C(n, k) * p^k * (1 - p)^(n - k)


Where:
- `p` = probability of success  
- `n` = number of trials  
- `k` = number of successes  
- `C(n, k)` = n choose k = n! / (k!(n-k)!)

## 🧠 Requirements

Make sure you have the following libraries installed:

```bash
pip install numpy matplotlib scipy
