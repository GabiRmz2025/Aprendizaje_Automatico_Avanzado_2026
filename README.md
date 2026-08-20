# Aprendizaje Automático Avanzado


`Objetivo General.` *Comprender, implementar y aplicar arquitecturas avanzadas de aprendizaje automático basadas en redes neuronales profundas usando Python y PyTorch, capacitando al estudiante para diseñar, entrenar, evaluar y desplegar modelos de Deep Learning en problemas reales de visión, lenguaje, generación de datos y toma de decisiones secuencial.*

`Introducción.` **Del Machine Learning clásico al Deep Learning**

### Semana 1

### Viernes · 4 hrs — Fundamentos y transición al Deep Learning
    1. Repaso del ML supervisado / no supervisado y sus límites
    2. ¿Por qué Deep Learning? Datos, cómputo (GPU) y representaciones aprendidas
    3. El perceptrón y el perceptrón multicapa (MLP)
    4. Funciones de activación y retropropagación (intuición)
    5. Ecosistema de librerías: NumPy, pandas, scikit-learn → PyTorch

### Sábado · 4 hrs — Tutorial de PyTorch
    1. Tensores, operaciones y device (CPU/GPU)
    2. Diferenciación automática con autograd
    3. Modelos con torch.nn, optimizadores y funciones de pérdida
    4. Bucle de entrenamiento, Dataset y DataLoader
    5. Ejercicio: primera red neuronal en PyTorch

`Módulo 1.` **Redes Neuronales Profundas**

### Semana 2 y Semana 3 (Viernes)

#### Viernes · 4 hrs — Entrenamiento de redes profundas
    1. Inicialización de pesos y gradiente que desaparece/explota
    2. Normalización: Batch Norm y Layer Norm
    3. Regularización: Dropout, weight decay, early stopping
    4. Optimizadores modernos: SGD con momento, RMSProp, Adam / AdamW
    5. Learning rate schedulers

#### Sábado · 4 hrs — Laboratorio de MLP profundo
    1. Preparación de datos y división train/val/test
    2. Implementación de un MLP profundo para clasificación multiclase
    3. Diagnóstico de sobreajuste/subajuste (curvas de aprendizaje)
    4. Registro de métricas con TensorBoard
    5. Guardado y carga de modelos (checkpoints)

#### Viernes (Semana 3) · 4 hrs — Buenas prácticas y ajuste
    1. Búsqueda de hiperparámetros (Optuna — intro)
    2. Reproducibilidad y control de experimentos
    3. Cierre de módulo: proyecto corto de clasificación

`Módulo 2.` **Visión por Computadora con Redes Convolucionales (CNN)**

### Semana 3 (Sábado) y Semana 4 (Viernes)

#### Sábado · 4 hrs — Fundamentos de CNN
    1. Convolución, stride, padding y campos receptivos
    2. Pooling y mapas de características
    3. Arquitecturas clásicas: LeNet, AlexNet, VGG, ResNet
    4. Laboratorio: CNN para clasificación de imágenes (MNIST / CIFAR-10)

#### Viernes · 4 hrs — Técnicas avanzadas de visión
    1. Transfer learning y fine-tuning con torchvision
    2. Data augmentation
    3. Detección y segmentación (panorama)
    4. Interpretabilidad visual (Grad-CAM)
    5. Cierre de módulo: clasificador con modelo preentrenado

`Módulo 3.` **Secuencias, Transformers, Modelos Generativos y Aprendizaje por Refuerzo**

### Semana 4 (Sábado) y Semana 5

#### Sábado · 4 hrs — Datos secuenciales y atención
    1. Redes recurrentes: RNN, LSTM y GRU
    2. Embeddings y representación de secuencias
    3. Mecanismo de atención y self-attention
    4. Arquitectura Transformer (encoder/decoder)
    5. Laboratorio: clasificación con un modelo basado en atención

#### Viernes · 4 hrs — Modelos de lenguaje y generativos
    1. Modelos preentrenados y fine-tuning (BERT/GPT — panorama)
    2. Autoencoders y Autoencoders Variacionales (VAE)
    3. Redes Generativas Antagónicas (GAN)
    4. Introducción a modelos de difusión
    5. Laboratorio: generación con un autoencoder / GAN sencillo

#### Sábado · 4 hrs — Aprendizaje por Refuerzo Profundo y cierre
    1. Elementos del RL: agente, entorno, política, recompensa, valor
    2. Ecuación de optimalidad de Bellman (repaso)
    3. Deep Q-Networks (DQN)
    4. Policy Gradients (visión general)
    5. Laboratorio con Gymnasium + PyTorch y presentación del proyecto final

**Evaluación:**

| Actividad         | Porcentaje |
|-------------------|:----------:|
| Tareas            |   30%      |
| Actividades       |   30%      |
| Proyecto Final    |   40%      |

**Recursos:**
- *Deep Learning* — Goodfellow, Bengio & Courville
- *Dive into Deep Learning* — Zhang, Lipton, Li & Smola — https://d2l.ai/
- *Deep Learning with PyTorch* — Stevens, Antiga & Viehmann
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- Vaswani et al. (2017) — *Attention Is All You Need*
- Goodfellow et al. (2014) — *Generative Adversarial Networks*
- Kingma & Welling (2013) — *Auto-Encoding Variational Bayes*
- Mnih et al. (2015) — *Human-level control through deep reinforcement learning (DQN)*
