
This Project's Philosophy
---

![alt text](evangelion_ui_comp_optimized.gif)

(more example gifs: https://imgur.com/a/evangelion-user-interfaces-gifs-uDeBs)

Neon Genesis Evangelion is a sci-fi anime from 1995 that promises more than it executes on plot but over-delivers on its vision for future graphical interfaces.

Maybe graphics are meant not only to be informative and easy to understand, but also grip an emotion of some kind.  

![](image.png)

![alt text](image-1.png)

gifsicle -O3 evangelion_ui_comp.gif -o evangelion_ui_comp_optimized.gif

Python Setup
---
```bash
python3 -m venv .venv

source .venv/bin/activate

pip install -r requirements.txt

pip list
```

Why Train in Pytorch and Infer in Rust
---

1. Development flexibility: PyTorch offers a rich ecosystem for model development, experimentation, and research. It's Python-based, which many data scientists and ML researchers are comfortable with.

2. Production performance: Rust is known for its speed and memory safety, making it an excellent choice for deploying models in production environments where performance is critical.

3. Resource efficiency: Rust can offer better memory management and lower resource usage compared to Python, which is beneficial for deployed models that need to handle high loads or run on resource-constrained devices.

4. Compilation to native code: Rust compiles to native machine code, potentially offering faster execution times compared to interpreted languages like Python.

5. Concurrency and parallelism: Rust has strong support for concurrent and parallel programming, which can be advantageous for handling multiple inference requests simultaneously.

6. Integration with systems programming: If the inference needs to be integrated into larger systems or low-level applications, Rust's systems programming capabilities make it a good fit.

7. Cross-platform deployment: Rust's ability to compile to various targets can simplify deployment across different platforms and architectures.

8. Reduced dependencies: A Rust implementation might have fewer runtime dependencies compared to a Python-based solution, potentially simplifying deployment and reducing security risks.

9. Type safety: Rust's strong type system can help catch certain classes of errors at compile-time, which could be beneficial for mission-critical applications.

Would you like me to elaborate on any of these points or discuss how one might go about implementing this PyTorch-to-Rust workflow?

I will edit this down so it comes off less cringe later.