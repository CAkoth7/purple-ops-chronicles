---
layout: post
title: "Ethical Challenges and Risks of AI in Cybersecurity"
date: 2025-12-18
topic: "AI Governance, Cybersecurity Ethics"
reading_time: "~12 minutes"
---

![AI and cybersecurity](../assets/images/posts/ethical-ai-cybersecurity/hero.jpg)

## Abstract

Artificial intelligence has become a central component of modern cybersecurity, enabling large-scale threat detection, automated response, and predictive security capabilities. However, its rapid adoption introduces a complex set of ethical and governance challenges that extend beyond technical performance.

This article examines the ethical risks associated with AI use in cybersecurity, focusing on privacy and surveillance concerns, bias and discrimination, transparency and explainability limitations, accountability and liability gaps, adversarial manipulation, and the dual-use nature of AI technologies.

Drawing on recent research, regulatory developments, and real-world incidents, the analysis highlights how poorly governed AI systems can undermine trust, fairness, and security effectiveness. The article argues that ethical AI in cybersecurity requires deliberate governance, clear accountability frameworks, explainable models, bias mitigation, and alignment with emerging regulatory standards such as the EU AI Act, NIST AI Risk Management Framework, and ISO/IEC AI-related standards.


---

## Challenge

Artificial intelligence has fundamentally transformed the cybersecurity landscape, offering unprecedented capabilities in threat detection, automated response systems, and predictive threat analysis. Over 75% of companies now integrate AI-driven solutions into their cybersecurity defences, a dramatic increase from just 40% five years ago. However, this rapid adoption has introduced profound ethical challenges that organizations must address responsibly. As AI becomes increasingly sophisticated and autonomous in security operations, critical ethical questions emerge around privacy, bias, transparency, accountability, and the dual-use nature of AI technologies. These challenges demand urgent attention from security leaders, policymakers, and technology developers to ensure that AI serves as a force for legitimate defence rather than a vector for harm (Newsroom, 2024).

---

## Privacy and Surveillance: Balancing security with individual rights 

One of the most significant ethical challenges in AI-powered cybersecurity concerns the tension between security objectives and privacy rights. AI systems excel at analysing vast amounts of network data, identifying patterns, and predicting potential threats; however, this capability raises profound questions about data collection practices and individual consent. AI-driven cybersecurity tools can monitor employee behaviour, analyse communication patterns, and track network activities at scales previously impossible with manual systems. While these capabilities enhance organizational security, they create opportunities for privacy violations and unauthorized data collection (Hackney, 2024).

The challenge becomes particularly acute in scenarios where organizations collect sensitive personal data ostensibly for security purposes but subsequently use this information for commercial, political, or administrative gain—purposes entirely disconnected from the original security mandate. Organizations must confront fundamental questions: Who controls the data collected by these AI systems? How can data be used only for legitimate security purposes rather than for surveillance that infringes upon civil liberties? Additionally, emerging threats such as adversarial data poisoning and deepfakes highlight how AI systems themselves can be weaponized to violate privacy at scale. The implementation of robust governance frameworks, transparent data practices, and explicit consent mechanisms becomes essential to navigate this ethical landscape responsibly ((KMPG, 2025).

---

## Bias, Discrimination, and Fairness

AI bias represents another critical ethical challenge with direct implications for cybersecurity effectiveness and organizational fairness. AI systems are trained on historical datasets that often reflect societal prejudices, incomplete information, and skewed representations of certain populations or behavioural patterns. When these biases enter cybersecurity AI models, they produce discriminatory outcomes that undermine both security effectiveness and organizational ethics (Hackney, 2024). The manifestations of bias in cybersecurity are particularly troubling. Biased AI systems may disproportionately flag certain user demographics, regions, or behavioural patterns as suspicious, creating an uneven security posture that unfairly targets specific groups. For example, a cybersecurity tool could incorrectly flag software primarily used by people of colour as malicious due to biased training data, causing unnecessary delays and creating a discriminatory security environment. Conversely, biased systems can fail to detect actual threats from groups underrepresented in training data, producing false negatives that compromise organizational security (Choudhary, 2024).

The consequences of AI bias extend beyond unfairness; they directly impact security operations through false positives and false negatives. Excessive false positives waste valuable security resources and create alert fatigue among security teams, reducing their ability to respond effectively to genuine threats. Biometric and deepfake detection systems have demonstrated particularly troubling racial disparities—research has shown that deepfake detectors misclassified real images of Black men as fake 39.1% of the time compared to 15.6% for white women. Addressing this challenge requires diverse and representative training datasets, continuous bias audits, and rigorous governance frameworks that prioritize fairness alongside accuracy in AI model development and deployment (Makhani, 2025).

---

## Transparency, Explainability, and the Black Box Problem

The opacity of many AI systems, particularly deep neural networks, creates a fundamental accountability challenge in cybersecurity operations. Complex AI models often operate as "black boxes," making decisions and generating security alerts without providing human-interpretable explanations for their reasoning. This lack of transparency undermines security professionals' ability to understand, verify, and trust automated security decisions, creating several cascading risks (Ajibola et al., 2025). When security teams cannot understand why an AI system flagged particular activities as threats or allowed others through, they cannot effectively verify whether decisions are justified, whether biases influenced outcomes, or whether the system is functioning as intended. This opacity becomes particularly problematic in high-stakes scenarios where security decisions impact organizational reputation, employee trust, and compliance standing. Furthermore, black-box AI systems are inherently more vulnerable to exploitation where attackers who cannot see how a system functions cannot be reliably prevented from finding weaknesses through adversarial techniques (BSI, 2022).

Explainable AI (XAI) emerges as a critical solution, providing interpretability and transparency that enables security professionals to understand, verify, and audit AI decisions. However, implementing XAI involves challenging trade-offs. More interpretable models often sacrifice accuracy for clarity, while efforts to explain black-box models' decisions may reveal proprietary information or create new attack vectors that malicious actors could exploit. Regulatory frameworks such as the EU AI Act increasingly mandate explainability for high-risk AI systems, reflecting growing recognition that transparency and accountability are essential and not optional components of responsible AI deployment in cybersecurity (EDPS, 2024).

---

## Accountability and Liability Gaps

Determining accountability when AI systems fail or cause harm remains profoundly unclear in existing legal and organizational frameworks. When an AI-powered intrusion detection system incorrectly flags legitimate activities as threats (false positives) or fails to detect actual threats (false negatives), responsibility becomes ambiguous. Should the developers who designed the system be held liable? Should the compliance or security teams responsible for insufficient testing bear responsibility? Should organizational leadership answer for prioritizing speed over safety? Should the deploying organization face full accountability? These questions remain largely unresolved in legal systems worldwide (Ajibola et al., 2025). This accountability gap becomes more complex when considering the multiple stakeholders involved in AI system lifecycles: data providers responsible for training data quality, developers who designed the system, deployers who implemented it, users who interact with it, and regulators who establish governance frameworks. Different jurisdictions take divergent approaches to assigning liability. Some regulatory frameworks channel responsibility toward a single entity, typically the AI developer or deploying organization, analogous to how nuclear law assigns responsibility to facility operators. However, this approach may prove inadequate when examining failures across organizations (Upmann, 2024).

International standards and frameworks are beginning to address this challenge. The EU AI Act imposes incident reporting obligations on both providers and deployers of high-risk AI systems, requiring prompt notification when malfunctions could impact health, safety, or critical infrastructure. The ISO/IEC 42001, 23894 standards provide governance guidance that helps organizations establish clear accountability matrices and oversight mechanisms. Furthermore, NIST AI Risk Management Framework (AI RMF) provides a structured approach to managing risk associated with AI systems throughout their lifecycle. In addition, European Agency for Cybersecurity (ENISA) provides various AI cybersecurity resources that offer practical guidance on enhancing AI system security throughout their lifecycle. Nevertheless, organizations currently struggle to implement clear accountability frameworks, particularly in incident response scenarios where multiple technical and organizational factors contributed to failures. Establishing comprehensive governance frameworks, conducting regular risk assessments, and building transparent oversight mechanisms remain essential steps toward adequate accountability (BSI, 2022).

---

## Adversarial Attacks and AI Poisoning

AI systems used in cybersecurity face unique vulnerabilities distinct from traditional software. Adversarial machine learning involves crafting deceptive inputs that intentionally deceive AI models into misclassifying threats. Unlike traditional cyberattacks that exploit implementation bugs or human weaknesses, adversarial attacks target the fundamental mechanisms through which AI models process information, making them difficult to detect using conventional security tools. Malware authors increasingly employ adversarial techniques to create variants that bypass AI-powered antivirus and endpoint detection systems. By making minimal modifications to malware code that preserve functionality but alter digital signatures, attackers can evade detection systems trained on historical malware signatures. More insidiously, adversarial attacks can be nearly invisible as they are small, carefully calculated changes to input data causing AI models to make dramatically incorrect decisions. A manipulated photo could bypass facial recognition security, or subtly modified audio could trick voice authentication systems into granting unauthorized access (Buckman, 2025).

AI poisoning undermines the integrity of AI models by manipulating their training data and processes, Data poisoning, a critical vulnerability, where attackers feed corrupted data into AI training pipelines to compromise model behavior. Poisoned AI models can redefine what constitutes normal or malicious behaviour, allowing attackers to bypass security controls or generate false alerts that disable security operations. This manipulation can degrade the model’s overall performance. The consequences extend across cybersecurity applications: compromised intrusion detection systems allow malicious traffic to pass through, poisoned fraud detection models enable financial crimes, and corrupted privileged access management systems grant unauthorized administrative access. Defence mechanisms must include anomaly detection algorithms, robust optimization strategies, ensemble learning approaches, real-time monitoring systems, and continuous model validation to detect and mitigate poisoning attempts before deployment. Moreover, red teams and advanced security professionals need to understand AI poisoning techniques, how they work, and the risks they pose. Awareness on these subjects need to be on cascaded to teams to improve partnership when dealing with issues (Goulding, 2025).

---

## The Necessary Evil: AI as Weapon and Shield

AI presents a fundamental dual-use challenge in cybersecurity: the same capabilities that strengthen organizational defence can be weaponized for offense. AI models may unintentionally discriminate against certain groups resulting in unfair cybersecurity policies, the boundary between security and intrusion is blurred when it comes to individuals’ privacy rights in AI-driven surveillance tools. Ethical hackers use AI for penetration testing and security audits, strengthening defences through controlled testing. However, malicious actors employ identical technologies to automate cyberattacks, generate convincing phishing emails at scale, create deepfakes for social engineering, develop tools that crack passwords with unprecedented speed, and evasion techniques. This asymmetry creates profound ethical challenges about responsible AI development and deployment (Vaishnavi, 2025).

Threat actors care little for AI ethics and readily deploy AI without restraint. However, legitimate companies must confront whether their AI development inadvertently enables malicious use through reverse engineering, unauthorized access, or knowledge transfer. The challenge intensifies with generative AI systems where researchers have already demonstrated how hidden text embedded within webpages can manipulate AI-powered search systems into generating misleading information. In 2024, Guardio Labs, in conjunction with Proofpoint reported “echospoofing” attacks against Proofpoint’s email protection service. A misconfiguration permitting spoofed outbound messages to be relayed through Proofpoint’s infrastructure was exploited by attackers, resulting in approximately three million perfectly authenticated spoofed emails circulating daily while impersonating brands such as Nike, Coca-Cola and Disney. Organizations must implement strict access controls, ensure adversarial testing, input sanitization, continuous model evaluation, and develop ethical guidelines for AI tool distribution, and maintain rigorous oversight of potentially dangerous capabilities to mitigate dual-use risks (Sibanda, 2025).

---

## Regulatory Frameworks and Governance

Emerging regulatory frameworks attempt to address these ethical challenges, though implementation remains uneven globally. The EU AI Act represents the most comprehensive regulatory approach, establishing a risk-based framework that imposes strict requirements on high-risk AI systems, including those used in cybersecurity. The Act mandates robustness and accuracy, requires data governance protections, and imposes incident reporting obligations for systems that could impact critical infrastructure or user safety. The EU AI Act's interaction with GDPR creates an integrated compliance landscape where high-risk AI systems involving personal data processing must satisfy both frameworks' requirements. This coordination reflects growing recognition that privacy, fairness, and security are interconnected rather than separate concerns. The Act also addresses explainability requirements, establishing that high-risk AI systems must be transparent and interpretable. These requirements directly address the black-box dilemma discussed earlier. Conducting Data Protection Impact Assessments (DPIAs) is necessary for high-risk activities as it involves assessing the potential risks to individuals’ rights and freedoms and measures to be implemented to mitigate these risks(Riedel & Idema, 2024). 

The Cyber Resilience Act (CRA) provides requirements for products containing digital elements (PDE) and is relevant for AI systems integrating such products. In addition, the Digital Resilience Act (DORA) forms uniform requirements for network and information systems security in financial entities. The NIST AI RMF provides a structured approach to manage risks throughout AI lifecycle. Lastly, the ISO standards – 42001, 23894, and 27090 provide guidelines for continual improvement of an Information Security Management System (ISMS) tailored for AI, AI risk management, and security and privacy guidelines for AI systems ((BSI, 2022). However, regulatory frameworks alone prove insufficient. Organizations must adopt comprehensive governance approaches that integrate ethics, technical expertise, and business strategy from the outset. This requires establishing clear accountability matrices, implementing auditable AI systems with comprehensive audit trails, conducting regular risk assessments using frameworks like ISO/IEC 23894, adopting explainable AI techniques, and building diverse, cross-functional teams that combine legal, technical, and ethical expertise (Stanford, 2025).

---

## Conclusion

The integration of AI into cybersecurity represents both tremendous opportunity and significant ethical peril. As organizations increasingly rely on AI for threat detection, automated response, and predictive security analysis, they must address ethical challenges proactively rather than reactively. The tension between security and privacy, the persistent challenge of bias and discrimination, the opacity of black-box systems, accountability gaps in existing frameworks, adversarial vulnerabilities, dual-use dilemmas, and emerging regulatory requirements create a complex ethical landscape. Responsible AI deployment in cybersecurity demands intentional design prioritizing transparency, fairness, and accountability alongside security effectiveness. Organizations must embrace governance frameworks that clarify accountability, implement rigorous bias audits and mitigation strategies, adopt explainable AI techniques despite trade-offs with accuracy, establish robust defences against adversarial attacks and data poisoning, and maintain ethical vigilance regarding dual-use technologies. Security leaders must recognize that ethical AI is not optional—it is essential for building trustworthy systems that protect organizational and individual interests simultaneously. Only through deliberate commitment to ethical principles, supported by appropriate governance frameworks and regulatory oversight, can AI serve as a genuinely protective force in cybersecurity rather than introducing new vulnerabilities and harms.

---

## References

Ajibola, O., Oladipupo Dopamu, & Olawunmi Olurin. (2025). Challenges and ethical implications of using AI in cybersecurity. International Journal of Science and Research Archive, 14(2), 294–304. https://doi.org/10.30574/ijsra.2025.14.2.0276

BSI. (2022). The EU AI Act and its interactions with Cybersecurity Legislation. BSI. https://www.bsigroup.com/en-IE/insights-and-media/insights/blogs/the-eu-ai-act-and-its-interactions-with-cybersecurity-legislation/

Buckman, B. (2025). What is Adversarial AI? Cybersecurity Threats & Defenses | Huntress. Huntress. https://www.huntress.com/cybersecurity-101/topic/adversarial-ai-cybersecurity-threats-defenses

Choudhary, U. (2024, December 24). Exploring the impact of AI bias on cybersecurity. Interface. https://interface.media/blog/2024/12/24/exploring-the-impact-of-ai-bias-on-cybersecurity/

EDPS. (2024, March 15). TechDispatch #2/2023 - Explainable Artificial Intelligence | European Data Protection Supervisor. Www.edps.europa.eu. https://www.edps.europa.eu/data-protection/our-work/publications/techdispatch/2023-11-16-techdispatch-22023-explainable-artificial-intelligence_en

Goulding, T. (2025, April 8). The rising danger of AI poisoning: When data turns toxic. Delinea; Delinea Inc. https://delinea.com/blog/ai-poisoning-when-data-turns-toxic

Hackney, H. (2024, April 24). AI Bias and the Dangers It Poses for the World of Cybersecurity - Architecture & Governance Magazine. Architecture & Governance Magazine. https://www.architectureandgovernance.com/artificial-intelligence/ai-bias-and-the-dangers-it-poses-for-the-world-of-cybersecurity/

KMPG (Ed.). (2025). The ethical use of AI in cybersecurity. KPMG. https://kpmg.com/us/en/articles/2025/ethical-ai-cybersecurity-balancing-security-privacy-digital-age.html

Makhani, F. (2025). The Hidden Risks of Relying on AI in Cybersecurity. Vikingcloud.com. https://www.vikingcloud.com/blog/disadvantages-of-ai-in-cybersecurity

Mohapatra, D. (2024, November 4). AI Explainability vs. Black-Box Models: The Ethical Dilemma. AI Governance & Responsible AI; AI Governance & Responsible AI. https://blog.cognitiveview.com/ai-explainability-vs-black-box-models-the-ethical-dilemma/

Newsroom. (2024, November 4). Ethical Implementation of AI in Cybersecurity in 2025. Modern Diplomacy. https://moderndiplomacy.eu/2024/11/04/ethical-implementation-of-ai-in-cybersecurity-in-2025/

Riedel, D., & Idema, S. (2024, September 12). Understanding intersection between EU’s AI Act and privacy compliance - Compact. Compact. https://www.compact.nl/articles/understanding-intersection-between-eus-ai-act-and-privacy-compliance/

Sibanda, I. (2025). Industry News 2025 Combating the Threat of Adversarial Machine Learning to AI Driven Cybersecurity. ISACA. https://www.isaca.org/resources/news-and-trends/industry-news/2025/combating-the-threat-of-adversarial-machine-learning-to-ai-driven-cybersecurity

Stanford, E. (2025, June 10). Who is responsible when AI acts autonomously & things go wrong? GLI. https://www.globallegalinsights.com/practice-areas/ai-machine-learning-and-big-data-laws-and-regulations/autonomous-ai-who-is-responsible-when-ai-acts-autonomously-and-things-go-wrong/

Upmann, P. (2024, December 18). Who is Accountable When an AI System Makes Erroneous Decisions That Cause Harm? AIGN. https://aign.global/ai-governance-insights/patrick-upmann/who-is-accountable-when-an-ai-system-makes-erroneous-decisions-that-cause-harm/

Vaishnavi. (2025, March 3). The Ethics of Using AI for Hacking and Security | Balancing Protection and Risk. WebAsha Technologies. https://www.webasha.com/blog/the-ethics-of-using-ai-for-hacking-and-security-balancing-protection-and-risk

---
