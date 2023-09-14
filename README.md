## Hi there 👋

I'm Chris, a high school student at Lynbrook High School.

### Blog

Checkout my blog at https://acciochris.github.io/

### My projects

- [Physics](https://acciochris.github.io/physics-notes)

  $$
  \begin{align*}
      \nabla\cdot\mathbf{E} &= \frac{\rho}{\epsilon_0} \\
      \nabla\times\mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
      \nabla\cdot\mathbf{B} &= 0 \\
      \nabla\times\mathbf{B} &= \mu_0\mathbf{J} + \mu_0\epsilon_0\frac{\partial \mathbf{E}}{\partial t}
  \end{align*}
  $$

- [Programming & Machine Learning](https://github.com/acciochris/machine-learning)

  ```python
  def evaluate(name, y_test, y_pred):
      print(f"Result for {name}:")
      print(f"precision: {precision_score(y_test, y_pred)}")
      print(f"recall: {recall_score(y_test, y_pred)}")
      print(f"f1: {f1_score(y_test, y_pred)}")
      print(f"matthews: {matthews_corrcoef(y_test, y_pred)}")
      plt.close()
      confusion = ConfusionMatrixDisplay.from_predictions(y_test, y_pred)
      confusion.plot()
  ```
