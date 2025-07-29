# Lorentz Transformation and Event Mapping

This simulation demonstrates how a fixed spacetime event transforms under Lorentz boosts as the observer's velocity increases.

## 🔭 What It Shows

- The original spacetime diagram (`x` vs `ct`)
- The **fixed event** (red dot)
- The **transformed coordinates** of that event (blue dot) as seen by a moving observer
- How the moving observer’s `x'` and `ct'` axes **rotate** with increasing β (v/c)
- When β approaches 1, the transformed frame **collapses onto the light cone**

## 📌 Physics Behind It

Using Lorentz transformation:

$$
\begin{aligned}
x' &= \gamma(x - vt) \\
ct' &= \gamma(ct - \beta x)
\end{aligned}
$$

As velocity increases, the moving frame's perspective of where and when an event occurred changes. This simulation brings that transformation to life by animating it on a spacetime diagram.

## ⚙️ Tools Used

- Python  
- NumPy  
- Matplotlib (for animation)  
- Google Colab

## 💡 Features

- Smooth animation from β = 0 to β = 0.99
- Fixed event remains stationary in rest frame
- Transformed coordinates update dynamically
- Light cone structure visible and invariant

## 📽 Demo Screenshot
![Lorentz Animation](Lorentz%20Transformation%20and%20Event%20Mapping%20in%20Special%20Relativity.png)


## 🔗 Interactive Use

You can run the simulation interactively with a velocity slider in:

- [Google Colab](https://colab.research.google.com/) (recommended)
- Jupyter Notebook (with `ipywidgets` installed)

> Unfortunately, GitHub does not support interactive sliders or dynamic animations directly.
>
> ✅ To share interactively:
> - Upload the `.ipynb` file to GitHub
> - Then open it in [Colab](https://colab.research.google.com/github/yourusername/yourrepo/blob/main/LorentzSimulation.ipynb) by replacing the URL
>
> Or host it via [nbviewer](https://nbviewer.org/) for read-only viewing

## 🧭 Future Plans

- Add multiple events (timelike, spacelike, lightlike)
- Show simultaneity lines per frame
- Explore Minkowski intervals interactively

---

📂 Part of the [Physics Simulations](https://github.com/yourusername/physics-simulations) collection
