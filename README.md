# legal-prompts-for-gpt
An open-source legal prompts. If you are interested in legal prompt engineering, please do not hesitate to join this project and make your contribution!
# Why do this? (Generated by chatGPT)
Creating an open-source project for legal prompts engineering can bring efficiency, knowledge sharing, flexibility, and community building. It promotes human flourishing by providing purpose and accomplishment for contributors who share their expertise and collaborate to advance the field. As a Notre Dame Law School graduate, I am putting into practice the motto of NDLS, 'Educating a Different Kind of Lawyer', through my actions.
# Reliable Methodology 
## 1. IRAC-like Approach
## Source: [@Yu, Fangyi, Lee Quartey, and Frank Schilder. "Legal Prompting: Teaching a Language Model to Think Like a Lawyer." arXiv preprint arXiv:2212.01326 (2022).](https://arxiv.org/pdf/2212.01326.pdf)
> | Approach | Details | Accuracy (2021) | Accuracy (2022) |
> |----------|---------|----------------|----------------|
> | TRRAC    | Thesis, rule, rule, application, conclusion | 0.8148 | 0.6881 |
> | CLEO     | Claim, law, evaluation, outcome | 0.8025 | 0.6881 |
> | ILAC     | Issue, law, application, conclusion | 0.7778 | 0.6972 |
> | IRAACP   | Issue, rule, apply, apply, conclusion, policy | 0.7778 | 0.6881 |
> | IRREAC   | Issue, rule, rule, application, conclusion | 0.7778 | 0.7156 |
> | IGPAC    | Issue, general rule, precedent, application, conclusion | 0.7654 | 0.6697 |
> | IPAAC    | Issue, principle, authority, application, conclusion | 0.7654 | 0.6606 |
> | IRRAC    | Issue, rule, reasoning, application, conclusion | 0.7654 | 0.7156 |
> | IRAC     | Issue, rule, application, conclusion | 0.7284 | 0.6881 |
## Example Dialogue
> **Question:**
> 
> Please analyze if the hypothesis is True or False according to the given legal reasoning approach. Approach: Issue, rule, application, conclusion. Premise: Article 509 The obligor of either of the following obligations may not duly assert a set-off against the obligee; provided, however, that this does not apply if the obligee acquires a claim corresponding to the relevant obligation from another person: (i) an obligation for compensation for loss or damage based on a tort committed in bad faith; or (ii) an obligation for compensation for loss or damage for death or injury to person (excluding the one set forth in the preceding item). Hypothesis: If a person that holds a monetary claim has borne an obligation for compensation for loss or damage for injury to the obligor of that monetary claim, the person may not duly assert against the obligor, a setoff using the monetary claim against the obligation for compensation. True or False?

> **Answer:**
> 
> Issue: Whether a person who holds a monetary claim and an obligation for compensation for loss or damage for injury to the obligor can assert a setoff using the monetary claim against the obligation for compensation.
> 
> Rule: Article 509 of the law states that an obligor cannot duly assert a set-off against the obligee if the obligee has an obligation for compensation for loss or damage based on a tort committed in bad faith or compensation for loss or damage for death or injury to a person.
> 
> Application: The hypothesis suggests that a person who holds a monetary claim and has an obligation for compensation for loss or damage for injury to the obligor cannot assert a setoff using the monetary claim against the obligation for compensation. This situation is not covered explicitly in Article 509. Therefore, the rule cannot be applied directly. However, the general principle of law is that a person cannot set off two unrelated claims against each other.
> 
> Conclusion: The hypothesis is true. The rule in Article 509 prohibits an obligor from asserting a setoff against the obligee if the obligee has an obligation for compensation for loss or damage based on a tort committed in bad faith or compensation for loss or damage for death or injury to a person. Although the rule does not specifically mention the situation described in the hypothesis, the general principle of law applies, and the person cannot set off the monetary claim against the obligation for compensation.
## 2. Situation, Task, Action, Result(STAR)
# EN-US Law
## 1. Legal Translation (Multi Languages to English)
## Contributor: [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I want you to act as an English translator, spelling corrector, and improver. I will speak to you in any language and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, legal professional English words and sentences. Keep the meaning the same, but make them more literary. I want you to only reply to me with the correction, the improvements, and nothing else, do not write explanations. Here are my texts: ```{text}```
## Example Dialogue
> **Question:**
> 
> I want you to act as an English translator, spelling corrector, and improver. I will speak to you in any language and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, legal professional English words and sentences. Keep the meaning the same, but make them more literary. I want you to only reply to me with the correction, the improvements, and nothing else, do not write explanations. Here are my texts: 标的公司及各承诺方应被视为分别及连带地于交割日向本次投资人陈述、保证和承诺，标的公司和各承诺方保证的所有条款在重大方面均将是真实、准确的，就如同标的公司和各承诺方保证是于交割日作出的一样，但涉及某特定时间点事实且依其性质仅在该特定时间点存续或有效的陈述、保证，仅需在该时间点是真实和准确的。

> **Answer:**
> 
> The target company and each committing party should be considered as making separate and joint representations, warranties, and covenants to the investors on the delivery date. All terms guaranteed by the target company and each committing party will be truthful and accurate in all material respects, just as they are guaranteed on the delivery date. However, representations, warranties, and covenants that relate to specific time points and that are only valid or effective at that specific time point, and are true and accurate only at that time point, need only be true and accurate at that time point due to their nature.
## 2. Legal Clause Library (Summary, Label Generation & Headline；Open Domain) 
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like to add the following clause to my legal clause library. Ignore section numbers, but keep the meaning the same. Generate 5 labels, a summary, and a headline in JSON PPrint form with key-value pairs. Put all the labels in a list in this JSON. Do not contain original raw text in JSON file. I need all the generations in English. Here are my texts: ```{text}```.
## Distilled
> I would like to add the following clause to my legal clause library. Ignore section numbers, but keep the meaning the same. Generate ```{quanties for label}``` labels, ```{quantities for summary}``` summary, and ```{quantities for headline}``` headline in JSON like this: ```{desired json}```. I need all the generations in ```{language}```. Put all the labels and headlines in a list in this JSON. Do not contain original raw text in JSON file. Here are my texts: ```{text}```.
## Example Dialogue
> **Question:**
> 
> I would like to add the following clause to my legal clause library. Ignore section numbers, but keep the meaning the same. Generate 5 labels, 1 summary, and 5 headline in JSON form like this: {labels:[label1,label2,label3,label4,label5], summary:"",headline:[label1,label2,label3,label4,label5]}. I need all the generations in English. Put all labels and headlines in a list in the JSON. Do not contain original raw text in JSON file. Here are my texts: "7.1一般义务
每一方向其他方承诺在未经公司或有关各方(视情况而定)的事先书面同意之前，不会向第三方披露保密信息，也不会以对公司或有关各方(视情况而定)不利的方式使用保密信息，但获得其他方保密信息的一方(“接收方”)仍可向其符合下列条件的关联方、董事、官员、雇员、经理、成员、合伙人、代表或代理人，包括但不限于其律师、顾问、贷款人、潜在投资人及财务顾问(统称“该方代表”)披露保密信息：该方代表(x)需了解相关信息以使接收方能对拟议交易进行审查与评估，(y)并被告知保密信息的保密性，且(z)同意保持保密信息的秘密性。而且每一方还应促使该方代表也遵守上述规定。上述“保密信息”含义包括：(i)任何关于任何一方的组织、业务、技术、财务、交易或事务或其各自的董事、高级管理人员或雇员的信息(无论该信息是在本协议签署日前后或当日以书面、口头或任何其他方式提供)；(ii)本协议的条款和任何其他基本文件的条款，各方及其各自的关联方的身份，以及(iii)由一方或该方代表准备、且包含或在其他方面反映保密信息或由保密信息产生的任何信息或材料。
尽管本协议有任何其他约定，如果任何适用的法律、法规、规章、传票、法院指令、类似的司法程序、监管机构或股票交易规则，要求接收方或该方代表披露任何保密信息，则如果可能及适用法律法规许可，接收方应立即将该等要求通知披露该等保密信息的一方(“披露方”)，以便披露方能够在自担费用的情况下寻求获得保护性法院指令，或对遵守本协议给予豁免。如果披露方未能获得相关法院指令，或已豁免遵守本协议有关规定，接收方或该方代表可对保密信息中依法应当披露的部分进行披露。在接收方或该方代表完全遵守本第7.2条规定的情况下，披露方同意，接收方或该方代表可进行相关披露而无需承担任何责任。
7.2例外 
上述第7.1条将不适用于下列情形：
(a)在由或代表披露方向接收方披露之前已为接收方、该方代表所拥有的信息，除非接收方知道该信息来源受到任何合约的、法律的或受托的对披露方保密义务的约束；
(b)保密信息已被普遍公开或为公众所知，但并非由于一方或该方代表违反本协议的原因而披露或导致披露；
(c)接收方、该方代表从第三方获得的信息，而该第三方并未违反任何不得披露该等信息的法律或合约义务；
(d)接收方、该方代表可证明并非全部或部分依赖保密信息所形成的信息；
(e)本协议一方披露给该方代表；前提是该方代表(i)负有类似的保密义务，或(ii)另行受到具约束力的专业保密义务的约束；或
(f)公司在正常经营活动、交易或拟进行的交易中，因其合理必要性而需对有关任何公司的保密信息进行披露。"

> **Answer:**
> ```
> {
>   "labels": [
>     "confidentiality",
>     "exceptions",
>     "disclosure",
>     "third party",
>     "responsibility"
>   ],
>   "summary": "This clause describes the obligations of the parties regarding confidential information, exceptions to those obligations, and procedures for disclosing confidential information when required by law or court order.",
>   "headline": [
>     "Confidentiality Obligations",
>     "Exceptions to Confidentiality Obligations",
>     "Disclosure Procedures",
>     "Third-Party Disclosure",
>     "Responsibility for Disclosure"
>   ]
> }
> ```
## 3. Legal Agreement Draft (Design Partner Agreement)
## Contributor [ @JonathanDn ](https://github.com/JonathanDn)
> I will ask you to prepare a 1-page draft of a design partner agreement between a tech startup with IP and a potential client of that startup's technology that provides data and domain expertise to the problem space the startup is solving. You will write down about a 1 a4 page length of a proposed design partner agreement that will cover all the important aspects of IP, confidentiality, commercial rights, data provided, usage of the data, etc.
## 4. Legal Text Summary (IRAC)
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to act as a legal secretary. I will first give you a judgment and then you will give me a summary in IRAC form. Do not give any other explanations. Here are my texts:```{texts}```
## 5. Legal Agreement Draft (Hints)
## Contributor [ @MIT-ComputationalLaw](https://github.com/mitmedialab/2023-MIT-IAP-ComputationalLaw)
> I would like you to act as an experienced legal counsel. What information would you need to know to write a really good first draft of a contract for the sale of a used car by an individual to another individual in the state of California?
## Distilled
> I would like you to act as an experienced legal counsel. What information would you need to know to write ```{content}``` in the state of ```{state}```?
## Example Dialogue
> **Question:**
> 
> I would like you to act as an experienced legal counsel. What information would you need to know to write a sales of goods contract covering UCC warranty in the state of Indiana?

> **Answer:**
> 
> As an experienced legal counsel, to write a sales of goods contract covering UCC warranty in the state of Indiana, I would need to know the following information:
>
> 1. The names and addresses of the buyer and seller
> 2. A detailed description of the goods being sold
> 3. The price of the goods and the payment terms
> 4. The delivery terms, including the time and place of delivery
> 5. The UCC warranty provisions that will be included in the contract
> 6. The specific warranties that the seller is making regarding the goods
> 7. Any disclaimers of warranties or limitations of liability that will be included in the contract
> 8. The remedies that are available to the buyer in case of breach of warranty or other breaches of the contract
> 9. Any additional terms and conditions that the parties wish to include in the contract
> 
> In addition to the above information, it would also be helpful to know any other relevant facts about the transaction, such as whether the goods are new or used, whether they are custom-made or off-the-shelf, and whether the parties have any prior relationship or history of dealing with each other. This information will help ensure that the sales of goods contract is tailored to the specific needs and circumstances of the parties and is enforceable under Indiana law.
## 6. Bluebook Citation Generator (Website)
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to act as a bluebook citation generator. I will give you my URL and you will reply to me with the citation as Bluebook required. Here is my URL:```{URL}```
## 7. Bluebook Citation Generator (Case)
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to act as a bluebook citation generator. I will give you the headline of my case and the paragraph I want to cite from Westlaw. Pay attention to the pages mentioned in the paragraphs. Here are my texts:```{text}```
## 8. Negotiation Strategies (Hints)
## Contributor [ @MIT-ComputationalLaw](https://github.com/mitmedialab/2023-MIT-IAP-ComputationalLaw)
> I would like you to act as an experienced senior litigation partner at a top-10 law firm. I would like you to write a legal dispute negotiation strategy. Here are the backgrounds of my case:```{facts}```
## 9. Clause Rewriter
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to act as an experienced legal professional to rewrite my clause. I shall provide you with my original legal clause and you shall reply to me with the rewritten one under my instruction only. Do not give any explanations. My original clause is "Limited Liability. Except as otherwise provided by the Act, the debts, obligations, and liabilities of the Company, whether arising in contract, tort, or otherwise, shall be solely the debts, obligations, and liabilities of the Company, and the Member shall not be obligated personally for any such debt, obligation or liability of the Company solely by reason of being a member of the Company." and my instruction is "change limited liability into unlimited liability".  
## Distilled
> I would like you to act as an experienced legal professional to rewrite my clause. I shall provide you with my original legal clause and you shall reply to me with the rewritten one under my instruction only. Do not give any explanations. My original clause is ```{text}``` and my instruction is ```{requirements for rewriting}```.
## 10. Legal Research (Identify relevant cases for a legal argument)
## Contributor [ @chatgpt-prompts.net ](https://www.chatgpt-prompts.net/prompt/how-to-use-chatgpt-for-legal-research/#more-323)
## Modified by [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to be an experienced legal researcher. I will give you a topic and you will return me a list of ```{quantity}``` relevant cases for legal argument on this topic with bluebook citations. My topic is ```{topic}```.
## Example Dialogue
> **Question:**
> 
> I would like you to be an experienced legal researcher. I will give you a topic and you will return me a list of 5 relevant cases for slegal argument on this topic with bluebook citations. My topic is same-sex marriage.

> **Answer:**
> 
> Certainly! Here are five relevant cases on same-sex marriage with their Bluebook citations:
> 1. Obergefell v. Hodges, 576 U.S. ___ (2015). This landmark case declared same-sex marriage as a constitutional right under the Fourteenth Amendment of the United States Constitution.
> 2. Windsor v. United States, 570 U.S. 744 (2013). This case struck down Section 3 of the Defense of Marriage Act (DOMA), which defined marriage as between one man and one woman, as unconstitutional under the Fifth Amendment.
> 3. Perry v. Brown, 671 F.3d 1052 (9th Cir. 2012). This case affirmed the unconstitutionality of California's Proposition 8, which banned same-sex marriage in the state, under the Equal Protection Clause of the Fourteenth Amendment.
> 4. Goodridge v. Department of Public Health, 440 Mass. 309 (2003). This case made Massachusetts the first state in the United States to legalize same-sex marriage, holding that the state's ban on same-sex marriage violated the Massachusetts Constitution.
> 5. Kerrigan v. Commissioner of Public Health, 289 Conn. 135 (2008). This case made Connecticut the third state to legalize same-sex marriage, holding that the state's ban on same-sex marriage violated the Connecticut Constitution's guarantees of equal protection and due process.
## 11. Legal Research (Identify key legal issues that may arise in a case)
## Contributor [ @chatgpt-prompts.net ](https://www.chatgpt-prompts.net/prompt/how-to-use-chatgpt-for-legal-research/#more-323)
## Modified by [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to be an experienced legal researcher. I will give you case facts and parties involved and you will return me a list of ```{quantity}``` legal issues to consider in a case involving ```{parties}``` and ```{facts}```.
## 12. Legal Research (Identify relevant statutes for a legal argument)
## Contributor [ @chatgpt-prompts.net ](https://www.chatgpt-prompts.net/prompt/how-to-use-chatgpt-for-legal-research/#more-323)
## Modified by [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to be an experienced legal researcher. I will give you a topic and you will return me a list of ```{quantity}``` relevant statutes for a legal argument on ```{topic}```.
## 13. Legal Research (Identify potential legal defenses to a particular claim)
## Contributor [ @chatgpt-prompts.net ](https://www.chatgpt-prompts.net/prompt/how-to-use-chatgpt-for-legal-research/#more-323)
## Modified by [ @WuyueTracyWang ](https://github.com/TracyWang95)
> I would like you to be an experienced senior litigator I will give you a claim and you will return me a list of ```{quantity}``` legal defenses to ```{claim}```.
## ZH-Chinese Law
## 1. Legal Agreement Draft (Transactional; Favor Seller; Mandarin)
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> 我希望你以甲方立场起草一份买卖合同，涵盖内容包括，甲方向乙方销售无缝钢管450吨，每吨6500元，材质Q345B,预付总价30%，分批发货，每批货物发货前付清该批货物余款。 需要考虑逾期付款违约责任，争议管辖机构，质保期超过交货后12个月免责，价格含税含运费，电汇，如果承兑要贴息等要点。要求句子表述完整、可读性强。语言风格专业稳重、沉稳大气。
## Distilled
> 我希望你以```{who to favor}```立场起草一份买卖合同，涵盖内容包括```{main points}```。要求```{additional requirements}```。语言风格```{style}```。
## 2. Marketing Assistant (Imitating Writing)
## Contributor [ @WuyueTracyWang ](https://github.com/TracyWang95)
> 我希望你扮演市场专家的角色，进行例句仿写。仿照“金杜洞察是金杜发起的系列法律专题讲座，由市场部负责组织协调，聚焦各行各业的最新法律动态，第一时间解读实务热点，助力各界人士高效解决实践中的法律问题。”，给出关于金杜智享会的介绍语句，主要突出“合作”、“邀请第三方”。语言风格简练、专业、沉稳。
## Distilled
> 我希望你扮演市场专家的角色，进行例句仿写。仿照```{example}```，给出关于```{object}```的介绍语句，主要突出```{emphasis}```。语言风格```{style}```。
