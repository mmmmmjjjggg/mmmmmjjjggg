import numpy as np
import matplotlib.pyplot as plt

# إنشاء نقاط لرسم القلب
t = np.linspace(0, 2 * np.pi, 1000)
x = 16 * np.sin(t)**3
y = 13 * np.cos(t) - 5 * np.cos(2 * t) - 2 * np.cos(3 * t) - np.cos(4 * t)

# رسم الشكل
plt.figure(figsize=(6, 6))
plt.plot(x, y, color="red")
plt.axis("off")  # إخفاء المحاور
plt.title("❤️", fontsize=20)
plt.show
