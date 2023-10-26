## Список вопросов к экзамену в рамках курса "Введение в распределенные технологии 2023/2024"

### Виртуализация и контейнеризация.

- Что такое виртуализация? Какие виды бывают, чем виртуализация отличается от контейнеризации и отличается ли? 

---

- Что такое docker, rkt, containerd? Как работает контейнеризация в одной из выбранных систем на выбор? (Полное объяснение с работой сетей и т.д) 

---

- Что такое kubernetes? Архитектура, работа служебных сервисов, методы организации развертывания контейнеров.

---

- Что такое Pod, Deployment - основные понятия, виды ресурсов + манифесты для каждого типа ресурсов

---

- Что такое Service и Ingress? - основные понятия, виды ресурсов + манифесты для каждого типа ресурсов

---

- Что такое  ConfigMap и Secrets? - основные понятия, виды ресурсов + манифесты для каждого типа ресурсов

---

- Как работают CNI, типы CNI, особенности развертывания и эксплуатации. 

---

- Что такое etcd и зачем он нужен? Как обновить Kubernetes?

### Блокчейн технологии

- Стек блокчейн-технологий. Уровневая модель стека.

[Статья на Springer](https://link.springer.com/chapter/10.1007/978-981-13-8775-3_8)

[Статья на Cehv](https://cehv.com/cehvs-blockchain-osi-model-thesis/)

---

- Основные недостатки блокчейн-сетей на примерах различных платформ

[Cтатья на ieee](https://ieeexplore.ieee.org/abstract/document/8592253)

[Статья на polkadot.network](https://polkadot.network/PolkaDotPaper.pdf)

---

- Распространенные типы уязвимостей и атак на блокчейн-сети.

[Cтатья на ieee](https://ieeexplore.ieee.org/abstract/document/9323061)

[Статья на Springer](https://link.springer.com/chapter/10.1007/978-981-15-1518-7_5)

[Статья на sciencedirect](https://www.sciencedirect.com/science/article/pii/S0167404818310927)

---

- Понятие хардфорка, его причины и последствия. Примеры хардфорков в различных сетях.

[Техническая статья](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4243070)

[Техническая статья](https://arxiv.org/abs/2102.10006)

---

- Экосистема Polkadot и ее архитектура. Типы и роли узлов в экосистеме.

[Github w3f](https://github.com/w3f/research/blob/master/docs/papers/OverviewPaper-V1.pdf)

[Cтатья на ieee](https://ieeexplore.ieee.org/abstract/document/9881859)

---

- Принцип shared security и его применение в блокчейн-сетях.

[Cтатья на ieee](https://ieeexplore.ieee.org/abstract/document/9881859)

[Статья на polkadot.network](https://wiki.polkadot.network/docs/learn-security)

[Техническая статья](https://dl.acm.org/doi/abs/10.1145/3530019.3531345)

---

- Механизм стейкинга токенов в различных сетях.

[Cтатья на ieee](https://ieeexplore.ieee.org/abstract/document/8123011)

[Техническая статья](https://www.mdpi.com/2227-7390/8/10/1782)

[Техническая статья](https://ijic.utm.my/index.php/ijic/article/view/272)

---

- Виды on-chain управления блокчейн-сетями.

[Техническая статья](https://hal.archives-ouvertes.fr/hal-02046787/document)

[Статья на polkadot.network](https://wiki.polkadot.network/docs/learn-governance)

---

- Блокчейн. Его основные характеристики.

[Про основные характористики](https://medium.com/@teamz/why-use-blockchain-a-case-of-transparency-immutability-and-security-ab60a688ddb1)

---

- Алгоритмы консенсуса. PoW, PoS, DPoS и прочие.
- 
[Перечисление основных алгоритмов консенсуса](https://media.sigen.pro/guides/1526)

---

- Сложность сети, размер блока, очередь транзакций.

[Блок и его содержимое](https://ethereum.org/ru/developers/docs/blocks/)

[Сложность сети](https://forklog.com/cryptorium/chto-takoe-heshrejt-i-slozhnost-majninga-kriptovalyut)

[Подробно про мемпул](https://www.blocknative.com/blog/mempool-intro)

---

- Проблема двойной траты, параметры транзакции, пропускная способность сети.

[Double spending](https://academy.binance.com/ru/articles/double-spending-explained)

[Пропускная способность](https://crypto.com/university/blockchain-scalability)

---

- EVM, smart contracts.

[Документация Ethereum](https://ethereum.org/en/developers/docs/evm/)

---

- Полнота по Тьюрингу EVM, прерывания EVM.

[Документация Ethereum](https://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf)

---

- Параметры ERC20, примеры программного кода.

[Документация OpenZeppelin](https://docs.openzeppelin.com/contracts/2.x/api/token/erc20)

---

- Параметры ERC721, ERC1155, примеры программного кода.

[Документация OpenZeppelin](https://docs.openzeppelin.com/contracts/2.x/api/token/erc721)

------

## List of Exam Questions for the "Introduction to Distributed Technologies 2023/2024" Course

### Virtualization and Containerization.

- What is virtualization? What are the types of virtualization, and how does virtualization differ from containerization, if at all?

---

- What is Docker, Rkt, and Containerd? Explain how containerization works in one of the selected systems of your choice, including networking and other relevant details.

---

- What is Kubernetes? Explain its architecture, the functioning of its core services, and the methods used to deploy containers.

---

- What are Pods and Deployments? Explain the key concepts and provide manifest examples for each type of resource.

---

- What are Services and Ingress? Explain the key concepts and provide manifest examples for each type of resource.
  
---

- What are ConfigMaps and Secrets? Explain the key concepts and provide manifest examples for each type of resource.

---

- How do Container Network Interfaces (CNI) work? What are the different types of CNIs, and what are the deployment and operational peculiarities?
---

- What is etcd, and why is it necessary? How can you update Kubernetes?

### Blockchain Technologies

- Blockchain technology stack. Layered model of the stack.

[Springer Article](https://link.springer.com/chapter/10.1007/978-981-13-8775-3_8)

[Cehv Article](https://cehv.com/cehvs-blockchain-osi-model-thesis/)

---

- Key disadvantages of blockchain networks using examples from various platforms.

[IEEE Article](https://ieeexplore.ieee.org/abstract/document/8592253)

[Polkadot.network Article](https://polkadot.network/PolkaDotPaper.pdf)

---

- Common types of vulnerabilities and attacks on blockchain networks.

[IEEE Article](https://ieeexplore.ieee.org/abstract/document/9323061)

[Springer Article](https://link.springer.com/chapter/10.1007/978-981-15-1518-7_5)

[ScienceDirect Article](https://www.sciencedirect.com/science/article/pii/S0167404818310927)

---

- Concept of hard fork, its reasons, and consequences. Examples of hard forks in different networks.
  
[Technical Article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4243070)

[Technical Article](https://arxiv.org/abs/2102.10006)

---

- Polkadot ecosystem and its architecture. Types and roles of nodes in the ecosystem.

[Github w3f](https://github.com/w3f/research/blob/master/docs/papers/OverviewPaper-V1.pdf)

[IEEE Article](https://ieeexplore.ieee.org/abstract/document/9881859)

---

- Shared security principle and its application in blockchain networks.

[IEEE Article](https://ieeexplore.ieee.org/abstract/document/9881859)

[Polkadot.network Article](https://wiki.polkadot.network/docs/learn-security)

[Тechnical Article](https://dl.acm.org/doi/abs/10.1145/3530019.3531345)

---

- Token staking mechanisms in various networks.
  
[IEEE Article](https://ieeexplore.ieee.org/abstract/document/8123011)

[Technical Article](https://www.mdpi.com/2227-7390/8/10/1782)

[Technical Article](https://ijic.utm.my/index.php/ijic/article/view/272)

---

- Types of on-chain governance in blockchain networks.

[Technical Article](https://hal.archives-ouvertes.fr/hal-02046787/document)

[Polkadot.network Article](https://wiki.polkadot.network/docs/learn-governance)

---

- Blockchain: Its key characteristics.

[About Key Characteristics](https://medium.com/@teamz/why-use-blockchain-a-case-of-transparency-immutability-and-security-ab60a688ddb1)

---

- Consensus algorithms: PoW, PoS, DPoS, and others.
  
[List of Main Consensus Algorithms](https://media.sigen.pro/guides/1526)

---

- Network difficulty, block size, transaction queue.

[Block and Its Contents](https://ethereum.org/ru/developers/docs/blocks/)

[Network Difficulty](https://forklog.com/cryptorium/chto-takoe-heshrejt-i-slozhnost-majninga-kriptovalyut)

[About Mempool in Detail](https://www.blocknative.com/blog/mempool-intro)

---

- Double spending problem, transaction parameters, network throughput.

[Double spending](https://academy.binance.com/ru/articles/double-spending-explained)

[Network Throughput](https://crypto.com/university/blockchain-scalability)

---

- EVM, smart contracts.

[Ethereum Documentation](https://ethereum.org/en/developers/docs/evm/)

---

- Turing completeness of EVM, EVM interrupts.
  
[Ethereum Documentation](https://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf)

---

- Parameters of ERC20 tokens, with code examples.

[OpenZeppelin Documentation](https://docs.openzeppelin.com/contracts/2.x/api/token/erc20)

---

- Parameters of ERC721 and ERC1155 tokens, with code examples.

[OpenZeppelin Documentation](https://docs.openzeppelin.com/contracts/2.x/api/token/erc721)

