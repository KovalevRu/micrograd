# Micrograd Implementation

Этот проект - моя реализация движка автоматического дифференцирования и нейронной сети (MLP) на чистом Python.

Я разработал этот код с нуля, разбираясь в фундаментальном устройстве нейросетей по видео Андрея Карпатого. Основная цель была в том, чтобы уйти от использования готовых библиотек вроде PyTorch и понять, как математика градиентного спуска работает на самом низком уровне.

**Что внутри:**
1. Класс Value: реализует хранение данных и автоматическое вычисление градиентов через chain rule.
2. Структура нейросети: самодельные классы для нейронов, слоев и многослойного перцептрона.
3. Обучение: написан цикл градиентного спуска, который позволил обучить модель до минимальной ошибки (loss порядка 10^-5)

Проект доказывает, что базовые принципы глубокого обучения можно воссоздать с помощью простых чисел и логики :)

---

# Micrograd Implementation

This is my from-scratch implementation of a scalar-valued autograd engine and a multi-layer perceptron (MLP) in pure Python.

I built this project to understand the inner workings of neural networks by following Andrej Karpathy's deep learning lectures. The goal was to avoid high-level frameworks and reconstruct the mechanics of backpropagation and gradient descent from first principles.

**Key components:**
1. Value class: handles data storage and automatic gradient calculation using the chain rule.
2. Neural network structure: custom classes for Neurons, Layers, and MLP.
3. Training: a functional gradient descent loop that achieves near-zero loss (approx. 10^-5) on training data.

This project serves as a proof of concept that deep learning foundations can be built using only basic Python and mathematics :).
