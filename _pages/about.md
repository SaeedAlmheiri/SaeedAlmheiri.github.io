---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.pub-year { font-size: 1.6em; font-weight: 600; color: #333; border-bottom: 1px solid #ddd; padding-bottom: 4px; margin-top: 0em; margin-bottom: 1em; }
.pub-entry { margin-bottom: 1.4em; padding-left: 0; line-height: 1.5; }
.pub-badges { display: inline; margin-right: 6px; }
.pub-badges a, .pub-badges span {
  display: inline-block; font-size: 0.75em; font-weight: bold; color: #fff;
  padding: 2px 8px; border-radius: 4px; margin-right: 3px; text-decoration: none;
}
.badge-pdf { background-color: #446E9B; }
.pub-badges .badge-bib { background-color: #dee2e6; color: #333;}
.badge-abs { background-color: #29ABE0; cursor: pointer; }
.badge-preprint { background-color: #2980b9; }
.pub-title { font-weight: bold; color: #333; }
.pub-authors { color: #4a76a8; }
.pub-venue { color: #888; font-size: 0.95em; }

.pub-abstract {
  display: none; background: #f9f9f9; border: 1px solid #ddd;
  border-radius: 4px; padding: 12px 16px; margin-top: 8px;
  font-size: 0.9em; color: #555; line-height: 1.6;
}
.pub-abstract.open { display: block; }
</style>

<script>
function toggleAbs(id) {
  document.getElementById(id).classList.toggle('open');
}
</script>

PhD student in Natural Language Processing at Mohamed Bin Zayed University of Artificial Intelligence (MBZUAI), focused on Role-Aware Large Language Models (RA-LLMs) for secure, policy-conditioned, and contextualized LLMs in multilingual organizational settings, under the supervision of Dr. [Fajri Koto](https://www.fajrikoto.com/) and Professor [Tim Baldwin](https://eltimster.github.io/www/). Before that, I received my Bachelor’s degree in Computer Science from Arizona State University.

My research interest lie in large language models (LLMs) Alignment, Access Control, User-Preference, Multilingual and Cultural-NLP.

Publications
======

<div class="pub-year">2026</div>

<div class="pub-entry">
  <span class="pub-title">Multilingual Idioms in Sentences and Conversations Across High-, Medium-, and Low-Resource Languages</span><br>
  <span class="pub-authors"><b>Saeed Almheiri*</b> | Bilal Elbouardi* | Salsabila Zahirah Pranida* | Irina Nikishina | Ashwath Rao B | Parameswari Krishnamurthy | Muhammad Cendekia Airlangga | Rifo Ahmad Genadi | Nguyễn Phan Gia Bảo | Amir Hossein Yari | Hawau Olamide Toyin | Nurdaulet Mukhituly | Mena Attia | Besher Hassan | Ahmad Fathan Hidayatullah | Tatsuki Kuribayashi | Haonan Li | Suma Bhat | Fajri Koto</span><br>
  <span class="pub-venue">Accepted at ACL 2026 Main</span>
</div>

<div class="pub-entry">
  <span class="pub-title">Cultural Benchmarking of LLMs in MSA and Arabic Dialectal Dialogue</span><br>
  <span class="pub-authors">Muhammad Dehan Al Kautsar* | <b>Saeed Almheiri*</b> | Momina Ahsan* | Bilal Elbouardi* | Younes Samih | Sarfraz Ahmad | Amr Keleg | Omar El Herraoui | Kareem Elzeky | Abed Alhakim Freihat | Mohamed Anwar | Zhuohan Xie | Junhong Liang | Mohammad Rustom Al Nasar | Preslav Nakov | Fajri Koto</span><br>
  <span class="pub-venue">Accepted at ACL 2026 Main</span>
</div>

<div class="pub-entry">
  <span class="pub-badges">
    <a href="https://arxiv.org/pdf/2601.05403" class="badge-preprint">preprint</a>
  </span>
  <span class="pub-title">Same Claim, Different Judgment: Benchmarking Scenario-Induced Bias in Multilingual Financial Misinformation Detection</span><br>
  <span class="pub-authors">Zhiwei Liu | Yupeng Cao | Yuechen Jiang | Mohsinul Kabir | Polydoros Giannouris | Chen Xu | Ziyang Xu | Tianlei Zhu | Md. Tariquzzaman | Triantafillos Papadopoulos | Yan Wang | Lingfei Qian | Xueqing Peng | Zhuohan Xie | Ye Yuan | <b>Saeed Almheiri</b> | Abdulrazzaq Alnajjar | Ming-Bin Chen | Harry Stuart | Paul Thompson | Prayag Tiwari | Alejandro Lopez-Lira | Xue Liu | Jimin Huang | Sophia Ananiadou</span><br>
  <span class="pub-venue">Accepted at ACL 2026 Findings</span>
</div>

<div class="pub-year">2025</div>

<div class="pub-entry">
  <span class="pub-badges">
    <a href="https://aclanthology.org/2025.acl-long.380.pdf" class="badge-pdf">pdf</a>
    <a href="https://aclanthology.org/2025.acl-long.380.bib" class="badge-bib">bib</a>
    <span class="badge-abs" onclick="toggleAbs('abs-3')">abs</span>
  </span>
  <span class="pub-title">Commonsense Reasoning in Arab Culture</span><br>
  <span class="pub-authors">Abdelrahman Sadallah | Junior Cedric Tonga | Khalid Almubarak | <b>Saeed Almheiri</b> | Farah Atif | Chatrine Qwaider | Karima Kadaoui | Sara Shatnawi | Yaser Alesh | Fajri Koto</span><br>
  <span class="pub-venue">In Proceedings of the Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025), Vienna, Austria, pp. 7695—7710.</span>
  <div class="pub-abstract" id="abs-3">
  Despite progress in Arabic large language models, such as Jais and AceGPT, their evaluation on commonsense reasoning has largely relied on machine-translated datasets, which lack cultural depth and may introduce Anglocentric biases. Commonsense reasoning is shaped by geographical and cultural contexts, and existing English datasets fail to capture the diversity of the Arab world. To address this, we introduce , a commonsense reasoning dataset in Modern Standard Arabic (MSA), covering cultures of 13 countries across the Gulf, Levant, North Africa, and the Nile Valley. The dataset was built from scratch by engaging native speakers to write and validate culturally relevant questions for their respective countries. spans 12 daily life domains with 54 fine-grained subtopics, reflecting various aspects of social norms, traditions, and everyday experiences. Zero-shot evaluations show that open-weight language models with up to 32B parameters struggle to comprehend diverse Arab cultures, with performance varying across regions. These findings highlight the need for more culturally aware models and datasets tailored to the Arabic-speaking world.
</div>
</div>

<div class="pub-entry">
  <span class="pub-badges">
    <a href="https://aclanthology.org/2025.findings-emnlp.247.pdf" class="badge-pdf">pdf</a>
    <a href="https://aclanthology.org/2025.findings-emnlp.247.bib" class="badge-bib">bib</a>
    <span class="badge-abs" onclick="toggleAbs('abs-2')">abs</span>
  </span>
  <span class="pub-title">Cross-Cultural Transfer of Commonsense Reasoning in LLMs: Evidence from the Arab World</span><br>
  <span class="pub-authors"><b>Saeed Almheiri*</b> | Rania Elbadry* | Mena Attia | Chenxi Wang | Preslav Nakov | Timothy Baldwin | Fajri Koto</span><br>
  <span class="pub-venue">In Findings of the Association for Computational Linguistics: EMNLP 2025, pp. 4593—4614.</span>
  <div class="pub-abstract" id="abs-2">
  Large language models (LLMs) often reflect Western-centric biases, limiting their effectiveness in diverse cultural contexts. Although some work has explored cultural alignment, the potential for cross-cultural transfer, using alignment in one culture to improve performance in others, remains underexplored. This paper investigates cross-cultural transfer of commonsense reasoning within the Arab world, where linguistic and historical similarities coexist with local cultural differences. Using a culturally grounded commonsense reasoning dataset covering 13 Arab countries, we evaluate lightweight alignment methods such as in-context learning (ICL) and demonstration-based reinforcement (DITTO), alongside baselines like supervised fine-tuning (SFT) and direct preference Optimization (DPO). Our results show that merely 12 culture-specific examples from one country can improve performance in others by 10% on average, within multilingual models. In addition, we demonstrate that out-of-culture demonstrations from Indonesia and US contexts can match or surpass in-culture alignment for MCQ reasoning, highlighting cultural commonsense transferability beyond Arab world. These findings demonstrate that efficient cross-cultural alignment is possible and offer a promising approach to adapt LLMs to low-resource cultural settings.
</div>
</div>

<div class="pub-entry">
  <span class="pub-badges">
    <a href="https://aclanthology.org/2025.ijcnlp-long.29.pdf" class="badge-pdf">pdf</a>
    <a href="https://aclanthology.org/2025.ijcnlp-long.29.bib" class="badge-bib">bib</a>
    <span class="badge-abs" onclick="toggleAbs('abs-1')">abs</span>
  </span>
  <span class="pub-title">
Role-Aware Language Models for Secure and Contextualized Access Control in Organizations</span><br>
  <span class="pub-authors"><b>Saeed Almheiri</b> | Yerulan Kongrat | Adrian Santosh | Ruslan Tasmukhanov | Josemaria Loza Vera | Muhammad Dehan Al Kautsar | Fajri Koto</span><br>
  <span class="pub-venue">In Proceedings of the International Joint Conference on Natural Language Processing & Asia-Pacific Chapter of the Association for Computational Linguistics (IJCNLP-AACL 2025), Mumbai, India, pp. 490—511.</span>
  <div class="pub-abstract" id="abs-1">
  As large language models (LLMs) are increasingly deployed in enterprise settings, controlling model behavior based on user roles becomes an essential requirement. Existing safety methods typically assume uniform access and focus on preventing harmful or toxic outputs, without addressing role-specific access constraints. In this work, we investigate whether LLMs can be fine-tuned to generate responses that reflect the access privileges associated with different organizational roles. We explore three modeling strategies: a BERT-based classifier, an LLM-based classifier, and role-conditioned generation. To evaluate these approaches, we construct two complementary datasets. The first is adapted from existing instruction-tuning corpora through clustering and role labeling, while the second is synthetically generated to reflect realistic, role-sensitive enterprise scenarios. We assess model performance across varying organizational structures and analyze robustness to prompt injection, role mismatch, and jailbreak attempts.
</div>
</div>
