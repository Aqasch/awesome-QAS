# awesome-QAS
A curated list of standout libraries, projects, tutorials, influential research papers, and essential resources focused on Quantum Architecture Search (QAS). This collection is designed to serve as a structured and thorough reference, empowering researchers and developers to accelerate their work and stay at the forefront of QAS advancements


## Table of contents


## Papers

- [DQAS: Differentiable quantum architecture search](https://arxiv.org/abs/2010.08561) A general framework automates quantum circuit design through end-to-end differentiable optimization, combining differentiable programming (gradient-based tuning), probabilistic programming (architectural uncertainty handling), and quantum programming (practical implementation). It demonstrates versatility by decomposing unitary operations into gates, mitigating noise in circuits, and optimizing layouts for combinatorial problems (e.g., QAOA). This framework accelerates the discovery of quantum advantages in NISQ-era devices while bridging interdisciplinary insights, offering a scalable tool for both practical applications and theoretical exploration in quantum computing.
- [Quantum circuit architecture search for variational quantum algorithms](https://arxiv.org/abs/2010.10217) enhances variational quantum algorithms (VQAs) by automatically optimizing ansatz design to balance expressivity and noise resilience in NISQ-era devices. While larger ansatze boost expressivity, they risk noise accumulation and poor trainability (e.g., barren plateaus). QAS efficiently identifies near-optimal circuit architectures, tested via IBM quantum hardware and simulators for data classification and quantum chemistry tasks. Results show QAS outperforms manual ansatz selection, mitigating noise, improving trainability, and achieving higher accuracy—demonstrating its potential to unlock robust quantum advantages in practical applications.
- [Quantum architecture search via deep reinforcement learning](https://arxiv.org/abs/2104.07715) automates quantum circuit design using deep reinforcement learning (DRL), addressing the challenge of creating efficient gate sequences for target states (e.g., multi-qubit GHZ states) without expert knowledge. The DRL agent, trained via A2C and PPO algorithms, accesses only Pauli-X/Y/Z expectation values and predefined quantum operations to optimize gate synthesis. This framework eliminates the need for embedded quantum physics principles in the agent, demonstrating generality for diverse DRL architectures and gate compilation studies, enabling resource-efficient quantum circuit development.
- [A GNN-based predictor for quantum architecture search](https://link.springer.com/article/10.1007/s11128-023-03881-x) accelerates circuit design for variational quantum algorithms (VQAs) by using a graph neural network (GNN) predictor to estimate circuit performance without full evaluations. Representing circuits as directed acyclic graphs (DAGs), a GNN encoder with asynchronous message-passing maps structures to performance features, mimicking quantum computations. Tested on 6- and 10-qubit variational quantum eigensolver (VQE) tasks, the predictor identifies high-performing circuits, filters weak candidates, and boosts sample efficiency—dramatically reducing computational costs in QAS.
- [Neural predictor based quantum architecture search](https://arxiv.org/abs/2103.06524) 

## Survays

- 
