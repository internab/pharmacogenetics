# Pharmacogenetics #
## Theory: Study the Central Dogma, PK/PD, and molecular structure of CYP enzymes. ##
เรื่อง Central Dogma, PK/PD และ CYP enzymes เป็นพื้นฐานสำคัญที่เชื่อมโยงระหว่างชีววิทยาโมเลกุลเข้ากับการตอบสนองต่อยาในร่างกาย
## Central Dogma คืออะไร ##
Central Dogma เป็นแนวคิดที่อธิบายการถ่ายทอดข้อมูลทางพันธุกรรมในสิ่งมีชีวิต โดยข้อมูลทางพันธุกรรมจะถูกเก็บอยู่ในรูปของ DNA หรือยีน จากนั้น DNA จะถูกถอดรหัส (Transcription) ไปเป็น RNA และ RNA จะถูกแปลรหัส (Translation) ไปเป็นโปรตีน ซึ่งโปรตีนจะทำหน้าที่ต่างๆ ภายในเซลล์เพื่อการดำรงชีวิตของสิ่งมีชีวิต 
แบ่งเป็น 2 ชั้นตอน:
1.    Transcription : DNA ถูกถอดรหัสเป็น mRNA ในนิวเคลียส
2.    Translation : mRNA ถูกแปลรหัสเป็นโปรตีนที่ Ribosome
## ขั้นตอนการสร้าง CYP 450 Proteins ##
### ขั้นตอนที่ 1: Transcription  การถอดรหัสจาก DNA ไปสู่ mRNA ###
เกิดขึ้นที่นิวเคลียสของ Hepatocyte (เซลล์ตับ) ซึ่งเป็นอวัยวะหลักในการแสดงออกของยีน CYP450
กระบวนการ มี 4 ขั้น:
>
1. **Initiation (การเริ่มต้น):**
เอนไซม์ RNA Polymerase II (isoform ที่ใช้สำหรับยีนที่ encode protein) จับกับบริเวณ Promoter บน DNA ซึ่งอยู่ต้นน้ำ (upstream) ของยีน CYP Promoter ประกอบด้วยลำดับเฉพาะ เช่น TATA Box (ลำดับ 5’-TATAAA-3’) ซึ่งเป็นที่จับของ Transcription Factor IID (TFIID) และ General Transcription Factors (GTFs) ก่อนที่ RNA Polymerase II จะเข้าจับได้ ทำให้เกิด Transcription Initiation Complex
>
2. **Elongation (การยืดสาย):**
RNA Polymerase II แยกเกลียว DNA (DNA Unwinding) และใช้ Template Strand (3’→5’) เป็นแม่แบบ สังเคราะห์สาย pre-mRNA ในทิศทาง 5’→3’ โดยการจับคู่เบสแบบ Complementary:
A บน DNA Template → U บน mRNA
T บน DNA Template → A บน mRNA
G บน DNA Template → C บน mRNA
C บน DNA Template → G บน mRNA
 สิ่งที่ได้คือ pre-mRNA ประกอบด้วย Exon (Expressed Sequence) และ Intron (Intervening Sequence)
>
3. **Termination (การสิ้นสุด):**
เมื่อ RNA Polymerase ถึง Termination Signal สาย pre-mRNA จะถูกปล่อยออกจาก DNA
>
4. **RNA Processing (การปรับแต่ง pre-mRNA):**
นี่คือขั้นตอนที่สำคัญที่สุดในการทำความเข้าใจผลของ CYP2D6*4
 มี 3กระบวนการหลัก:
 >
> 4.1) 5’ Capping: ต่อ 7-methylguanosine (m7G) cap เข้ากับปลาย 5’ ของ pre-mRNA ทันทีที่เริ่มสังเคราะห์ มีหน้าที่สองอย่าง:
    • ป้องกัน pre-mRNA จากการถูกย่อยโดย 5’-exonuclease
    • ช่วยให้ Ribosome จดจำและจับ mRNA ในขั้นตอน Translation ได้
>
> 4.2) 3’ Polyadenylation: เพิ่ม Poly-A Tail (สาย adenosine ต่อๆ กัน ~200 ตัว) เข้าที่ปลาย 3’ ของ mRNA ช่วยเพิ่มอายุของ mRNA และช่วยในกระบวนการ export ออกจากนิวเคลียส
>
> 4.3) RNA Splicing (กระบวนการสำคัญที่สุดสำหรับ CYP2D6*4): บริเวณ Intron-Exon Boundary มีลำดับนิวคลีโอไทด์ที่ได้รับการอนุรักษ์ไว้สูงมาก กฎทั่วไปคือ Intron จะเริ่มต้นด้วย GT และสิ้นสุดด้วย AG (เรียกว่า GT-AG Rule) การกลายพันธุ์ที่ตำแหน่ง Splice Site เหล่านี้สามารถทำให้เกิด: Exon Skipping (ข้ามการรวม exon บางตัว), Intron Retention (รักษา intron ไว้ใน mRNA), หรือการสร้าง Cryptic Splice Site ใหม่ ผลที่ตามมาคือ mRNA ที่ผิดปกติ ซึ่งอาจทำให้ได้โปรตีนที่ truncated หรือถูก degraded 
ในสัตว์เลี้ยงลูกด้วยนม เมื่อมี Premature Termination Codon (stop codon ที่เกิดก่อนกำหนด) ที่อยู่ห่างจาก exon-exon junction มากกว่า ~50 นิวคลีโอไทด์ขึ้นไป เซลล์จะรับรู้ว่านี่คือ mRNA ที่ผิดปกติและกำจัดมันผ่านกระบวนการ Nonsense-Mediated Decay (NMD) ซึ่งทำให้ mRNA ที่ผิดปกติถูกทำลายก่อนที่จะถูกแปลรหัสเป็นโปรตีน 
ผลสุดท้ายจาก RNA Processing ที่สมบูรณ์คือ Mature mRNA ที่มีเฉพาะ Exon ต่อกัน พร้อม 5’ Cap และ Poly-A Tail แล้วจึงออกจากนิวเคลียสผ่าน Nuclear Pore Complex ไปสู่ Cytoplasm
### ขั้นตอนที่ 2: Translation  การแปลรหัสจาก mRNA เป็น CYP450 Protein ###
เกิดที่ Rough Endoplasmic Reticulum (RER) — เนื่องจาก CYP450 เป็น Membrane-bound Protein จึงถูกสังเคราะห์บน Ribosome ที่ฝังตัวอยู่บน RER
กระบวนการมี 4 ขั้นตอน:
1. Initiation: Ribosome (ประกอบด้วย Small subunit 40S และ Large subunit 60S ในยูคาริโอต) จับกับ 5’ Cap ของ mRNA และเคลื่อนที่ไปตามสาย mRNA ในทิศทาง 5’→3’ จนพบ Start Codon (AUG) ซึ่ง Methionine-tRNA (Met-tRNA) เข้าจับที่ P-site ของ Ribosome
2. Elongation: Aminoacyl-tRNA (tRNA ที่บรรจุกรดอะมิโน) เข้าจับที่ A-site โดยการจับคู่ anticodon บน tRNA กับ codon บน mRNA จากนั้น peptide Bond เกิดขึ้นระหว่างกรดอะมิโนที่ A-site และสายโพลีเปปไทด์ที่ P-site และ Ribosome เคลื่อนที่ไปอีก 1 codon (Translocation) ทำให้ A-site ว่างรับ aminoacyl-tRNA ตัวใหม่ ทุก Codon บน mRNA (triplet of nucleotides) จะ encode กรดอะมิโน 1 ตัว โดย Genetic Code ประกอบด้วย 64 codon (4³) ซึ่ง 61 codon encode กรดอะมิโน 20 ชนิด และอีก 3 codon เป็น Stop Codon
ความสำคัญต่อ CYP2D6*4: เมื่อ Frameshift เกิดขึ้นจากการ Splicing ผิดปกติ การอ่าน codon จะเปลี่ยนไปทั้งหมดตั้งแต่ตำแหน่งนั้น ทำให้กรดอะมิโนที่ถูก encode เปลี่ยนไปจากปกติ และในไม่ช้าจะพบ Stop Codon ก่อนกำหนด *
3. Termination: เมื่อ Ribosome พบ Stop Codon (UAA, UAG, หรือ UGA) ซึ่งไม่มี tRNA ที่จับคู่ได้ Release Factor จะเข้าจับที่ A-site และกระตุ้นให้สายโพลีเปปไทด์ถูกปล่อยออก Ribosome แยกออกเป็น 40S และ 60S subunit
4. Post-translational Modification: สายโพลีเปปไทด์ที่ได้ต้องผ่านการปรับแต่งเพิ่มเติมเพื่อให้ทำงานได้:
 - Protein Folding: โปรตีนพับตัวเป็นโครงสร้างสามมิติที่ถูกต้อง (ช่วยโดย Chaperone Proteins)
 - Heme Incorporation: โมเลกุล Heme (Iron-Protoporphyrin IX) ถูกสอดเข้าไปในโปรตีน CYP450 ที่ Active Site จุดนี้คือ Cofactor สำคัญที่ทำให้เกิด Catalysis
 - Membrane Anchoring: โปรตีนถูกฝังลงในเยื่อหุ้มของ Smooth Endoplasmic Reticulum ผ่าน N-terminal transmembrane domain
## Pharmacokinetics (PK) “ร่างกายทำอะไรกับยา” ##
Pharmacokinetics คือการศึกษาเชิงปริมาณว่าร่างกายจัดการกับยาอย่างไร ตั้งแต่ยาเข้าสู่ร่างกายจนกระทั่งถูกขับออก อธิบายด้วยหลัก ADME ดังนี้:
 - **A : Absorption (การดูดซึม)**
ยาที่รับประทานต้องละลายในทางเดินอาหารและผ่านเยื่อบุลำไส้เข้าสู่กระแสเลือด ปัจจัยที่มีผลต่อ Absorption ได้แก่ ค่า pKa ของยา, pH ของสภาพแวดล้อม, lipophilicity (log P), และ Transporter proteins (เช่น P-glycoprotein)
 - **D — Distribution (การกระจาย)**
ยาในกระแสเลือดถูกพาไปทั่วร่างกาย โดยมีปัจจัยสำคัญคือ Volume of Distribution (Vd) และ Protein Binding (เช่น การจับกับ Albumin หรือ Alpha-1-acid glycoprotein) ยาที่จับกับโปรตีนในพลาสมาจะไม่ออกฤทธิ์และไม่ถูก metabolize จนกว่าจะถูกปล่อยออกมา
 - **M — Metabolism (การเปลี่ยนแปลง)**
การเผาผลาญยาเกิดขึ้นเป็นหลักในตับ และแบ่งเป็น 2 Phase:
Phase I Metabolism: CYP450 เร่งปฏิกิริยา Oxidation (Hydroxylation, N-dealkylation, O-dealkylation, S-oxidation ฯลฯ), Reduction, หรือ Hydrolysis เพื่อเพิ่ม Polar Group ให้กับโมเลกุลยา เพื่อเตรียมสำหรับ Phase II ผลิตภัณฑ์อาจมีฤทธิ์เพิ่มขึ้น ลดลง หรือเท่าเดิม (บางกรณีเป็นผลิตภัณฑ์ Toxic)
Phase II Metabolism: Conjugation ของ Polar Group กับโมเลกุลต่างๆ ได้แก่ Glucuronic Acid (Glucuronidation โดย UGT), Sulfate (Sulfation), Glutathione, Acetyl group ผลิตภัณฑ์ที่ได้มักมีขนาดโมเลกุลใหญ่, ละลายน้ำได้ดีขึ้นมาก, และ inactive พร้อมสำหรับการขับออกทางไตหรือน้ำดี CYP Isoforms มีหลักที่รับผิดชอบการเผาผลาญยา
 - **E — Excretion (การขับออก)** Metabolite ที่ผ่าน Phase II แล้วถูกขับออกทาง:
ไต (Renal Excretion): metabolite ที่มีน้ำหนักโมเลกุลต่ำและละลายน้ำได้ดี → ขับออกทางปัสสาวะ
น้ำดี (Biliary Excretion): metabolite ที่มีน้ำหนักโมเลกุลสูง (>500 Da) → ขับออกทางน้ำดีและอุจจาระ (อาจเกิด Enterohepatic Circulation)
### พารามิเตอร์ทาง PK ที่สำคัญ: ###
 - Half-life (t₁/₂): เวลาที่ความเข้มข้นยาในเลือดลดลงครึ่งหนึ่ง (ผู้ที่มี CYP เร็วกว่าจะมี t₁/₂ สั้นกว่า)
 - Area Under Curve (AUC): ปริมาณยาที่ร่างกายได้รับโดยรวม (ผู้ที่ metabolize ช้า = AUC สูงกว่า)
 - Clearance (CL): ปริมาตรเลือดที่ถูก “ทำความสะอาด” จากยาต่อหน่วยเวลา
 - Bioavailability (F): สัดส่วนยาที่เข้าสู่ Systemic Circulation เทียบกับที่ได้รับทั้งหมด
## Pharmacodynamics (PD) — “ยาทำอะไรกับร่างกาย” ##
Pharmacodynamics คือการศึกษาผลทางชีววิทยาของยาต่อร่างกาย ซึ่งกำหนดโดย:
กลไกการออกฤทธิ์:
1. Receptor Agonism/Antagonism:
ยาจับกับ Receptor และกระตุ้น (Agonist) หรือขัดขวาง (Antagonist) การส่งสัญญาณ เช่น Metoprolol ที่เป็น β₁-Adrenergic Antagonist ขัดขวางการจับของ Norepinephrine ที่หัวใจ
2. Enzyme Inhibition:
ยาจับกับ Active Site หรือ Allosteric Site ของ Enzyme เพื่อยับยั้งการทำงาน เช่น Omeprazole ยับยั้ง H⁺/K⁺-ATPase (Proton Pump) บนผนังกระเพาะอาหาร
3. Ion Channel Modulation:
ยาเปิดหรือปิด Ion Channel เช่น Diazepam เพิ่มความถี่การเปิดของ Cl⁻ Channel บน GABA_A Receptor
4. Transporter Inhibition:
ยาขัดขวาง Transport Protein เช่น Clopidogrel (ในรูป Active Metabolite) จับแบบ Irreversible กับ P2Y₁₂ Receptor บน Platelet ขัดขวางการจับของ ADP ป้องกันการรวมตัวของ Platelet

# **การวิเคราะห์พันธุกรรม🧬** 
## Tools: Navigate PharmVar. Track exact nucleotide changes for CYP2D6*4 and CYP2C19*17.
## PharmVar (pharmvar.org)
>คือ ฐานข้อมูลระดับนานาชาติที่รวบรวมตัวแปรทางพันธุกรรมของยีนที่เกี่ยวข้องกับการ metabolize ยา ใช้ระบบ Star Allele Nomenclature โดย *1 คือ allele ปกติที่ใช้เป็น reference ส่วน allele อื่นๆ
>จะถูกจัดระดับการทำงานเป็น Normal function, Decreased function, No function หรือ Increased function

> **ตัวอย่าง**
### **CYP2D6*4 — No Function Allele**
- **SNP หลัก : 1847G>A (rs3892097)** ใน Intron 3
    การเปลี่ยน G เป็น A ที่ตำแหน่งนี้ทำลาย 5’ Splice site ของ Intron 3 ซึ่งเป็นลำดับ GT ที่ Spliceosome ใช้จดจำจุดตัด เมื่อลำดับนี้เสียไป Spliceosome ไม่สามารถระบุจุดตัดได้ถูกต้อง Intron 3 จึงไม่ถูกตัดออกและติดอยู่ใน mRNA
    เมื่อ Ribosome นำ mRNA ที่ผิดปกตินี้ไป translate ลำดับของ Intron ที่แทรกเข้ามาทำให้ Reading frame เลื่อน (Frameshift) Ribosome เจอ Premature stop codon ก่อนกำหนดและหยุดสร้างโปรตีน โปรตีนที่ได้จึงสั้น ผิดรูป และไม่มีกิจกรรมเอนไซม์
- ผู้ที่มี genotype *4/*4 จัดเป็น **Poor Metabolizer (PM)** พบ *4 allele ในความถี่ประมาณ 20-25% ในประชากรยุโรป
### **CYP2C19*17 — Increased Function Allele**
- **SNP หลัก : −806C>T (rs12248560)** ใน Promoter region
การเปลี่ยน C เป็น T ที่ตำแหน่ง −806 บริเวณ Promoter สร้าง consensus binding site ใหม่สำหรับ GATA Transcription Factor ซึ่งแสดงออกในตับ เมื่อ GATA จับกับ Promoter ได้มากขึ้น RNA Polymerase ทำงานมากขึ้น mRNA CYP2C19 ถูกสร้างในปริมาณสูงขึ้น และโปรตีน CYP2C19 ที่ผลิตออกมามีมากกว่าปกติ โครงสร้างโปรตีนแต่ละตัวปกติ แต่ปริมาณที่มากกว่าทำให้รวมกันเมแทบอไลซ์ยาได้เร็วและมากกว่าคนทั่วไป
- ผู้ที่มี genotype *17/*17 จัดเป็น **Ultrarapid Metabolizer (UM)** พบ *17 allele ประมาณ 21% ในคนยุโรป 16% ในคนแอฟริกัน-อเมริกัน และเพียง 3% ในคนเอเชีย
# เอนไซม์หลัก (Big 5)
- ในการทำงานของตับ เอนไซม์ในระบบ Cytochrome P450 ถือเป็นเอนไซม์หลักในกระบวนการ Metabolism Phase 1 โดยเอนไซม์กลุ่ม "Big 5" มีบทบาทในการเผาผลาญยา (Metabolism) มากกว่า 75% ของยาทั้งหมดที่ใช้ในทางการแพทย์
- เอนไซม์ในระบบ Cytochrome P450 ซึ่งจะเรียกว่า "Big 5" ได้แก่ CYP2D6, CYP2C19, CYP2C9, CYP3A4 และ CYP3A5 ข้อมูลสรุปของเอนไซม์แต่ละชนิดมีดังนี้:
###
| เอนไซม์ | % ยาที่ย่อย | ตำแหน่งยีน | ยาสำคัญที่ขึ้นกับเอนไซม์ | ความแปรปรวนทางพันธุกรรม |
| :--- | :---: | :---: | :--- | :--- |
| **CYP2D6** | ~25% | โครโมโซม 22 | ยาต้านเศร้า, Codeine, Beta-blocker | สูงมาก — >100 Star Alleles |
| **CYP2C19** | ~10-15% | โครโมโซม 10 | Clopidogrel, PPIs, SSRIs | สูงมาก — สำคัญในชาวเอเชีย |
| **CYP2C9** | ~10-15% | โครโมโซม 10 | Warfarin, NSAIDs, Phenytoin | ปานกลาง — สำคัญต่อยาที่มี Index แคบ |
| **CYP3A4** | ~40-50% | โครโมโซม 7 | ยามากกว่าครึ่งหนึ่งของทั้งหมด! | ต่ำ — แต่ถูกยาอื่นยับยั้ง/กระตุ้นได้มาก |
| **CYP3A5** | ~5-10% | โครโมโซม 7 | Tacrolimus, ยากดภูมิ | แตกต่างมากระหว่างชาติพันธุ์ |

> หลักการสำคัญในการทำงาน
ในทางสรีรวิทยา เลือดที่มีสารอาหารและยาจะไหลผ่าน Portal Vein เข้าสู่ตับ และกระจายตัวเข้าสู่เซลล์ตับ (Hepatocytes) ซึ่งภายในเซลล์จะมี Smooth Endoplasmic Reticulum เป็นที่อยู่ของเอนไซม์เหล่านี้ ยาจะถูกเปลี่ยนโครงสร้างให้มีความเป็นขั้ว (Polar) มากขึ้น ผ่านกระบวนการ Metabolism Phase I ทำให้ได้ Active metabolite หรือ Inactive metabolite เป็นสารที่ขับออกได้ง่ายขึ้น (มักไม่มีฤทธิ์แล้ว)


## Simulation: Map "Prodrug vs. Active Drug." Build lists for activation vs. clearance.       
## รายชื่อยา 10 ชนิดที่สำคัญ 💊
> โดยแบ่งกลุ่มตามกลไกการออกฤทธิ์ระหว่าง ยาต้นแบบ (Prodrugs)  และ ยาที่ออกฤทธิ์ทันที (Active Drugs)
- กลุ่มยาต้นแบบที่ต้องอาศัยการกระตุ้น (Prodrugs - Require CYP Activation)
สารประกอบเหล่านี้จะถูกบริหารเข้าสู่ร่างกายในรูปแบบที่ยังไม่ออกฤทธิ์ หรือมีฤทธิ์น้อยมาก โดยต้องอาศัยเอนไซม์ CYP ในการเปลี่ยนโครงสร้างให้เป็นสารอนุพันธ์ (Thiol derivative) หรือสารเมแทบอไลต์ที่สามารถออกฤทธิ์ในการรักษาได้
- กลุ่มยาที่ออกฤทธิ์ทันทีและอาศัยการกำจัด (Active Drugs - Require CYP Clearance)
ยาเหล่านี้สามารถออกฤทธิ์ได้ทันทีเมื่อเข้าสู่ร่างกาย แต่ต้องอาศัยเอนไซม์ CYP ในการสลายให้กลายเป็นสารที่ไม่ไม่ออกฤทธิ์ (Inactive metabolites) เพื่อเตรียมขับออกจากร่างกาย

| ลำดับ | ประเภทของยา | ชื่อยา | ข้อบ่งใช้ / กลุ่มยา | เอนไซม์ CYP ที่เกี่ยวข้อง | การออกฤทธิ์ / สารอนุพันธ์ (Metabolite) |
| :---: | :--- | :--- | :--- | :--- | :--- |
| **1** | Prodrug | Clopidogrel | ยาต้านเกล็ดเลือด  | CYP2C19  | ต้องถูกเปลี่ยนเป็น Thiol derivative  |
| **2** | Prodrug | Codeine |ยาระงับปวดในกลุ่มโอปิออยด์  | CYP2D6  | ต้องถูกเปลี่ยนเป็น Morphine  |
| **3** | Prodrug | Tamoxifen  | ใช้ในการรักษามะเร็งเต้านม |CYP3A4/5, CYP2D6  | ต้องถูกเปลี่ยนเป็น Endoxifen และ 4-Hydroxytamoxifen  |
| **4** | Prodrug | Tramadol  | ยาแก้ปวด | CYP2D6 | ต้องถูกเปลี่ยนเป็น O-desmethyltramadol  |
| **5** | Prodrug | Losartan | ยาลดความดันกลุ่ม ARB  |CYP2C9, CYP3A4 | ต้องถูกเปลี่ยนเป็น E-3174  |
| **6** | Active Drug |Omeprazole  | ยาลดการหลั่งกรดในกระเพาะอาหาร  | CYP2C19 | [ออกฤทธิ์ได้ทันที แต่ต้องอาศัยเอนไซม์สลายให้อยู่ในรูปไม่ออกฤทธิ์เพื่อขับออก  |
| **7** | Active Drug | Diazepam | ยาในกลุ่มเบนโซไดอะซีปีน  | CYP2C19, CYP3A4  | ออกฤทธิ์ได้ทันที แต่อาศัยเอนไซม์เผาผลาญเป็นหลัก  |
| **8** | Active Drug | Warfarin  | ยาต้านการแข็งตัวของเลือด | CYP2C9  | ออกฤทธิ์ได้ทันที แต่ถูกกำจัดออกจากร่างกายผ่านเอนไซม์นี้เป็นหลัก  |
| **9** | Active Drug | Amiodarone  | ยาต้านการเต้นของหัวใจที่ผิดจังหวะ | CYP3A4, CYP2C8 | ออกฤทธิ์ได้ทันที แต่อาศัยเอนไซม์เหล่านี้ในการสลาย  |
| **10** | Active Drug |Phenytoin  | ยาต้านอาการชัก  |CYP2C9 (และ CYP2C19)  | ออกฤทธิ์ได้ทันที แต่อาศัยเอนไซม์เหล่านี้ในการสลาย |

## Project: Draft CYP2D6 and CYP2C19 sections of the "Big 5" Cheat Sheet.
![Uploading image.jpeg…]()

## เอกสารอ้างอิงทางคลินิก: CYP Enzymes
### **CYP2D6**
> โครโมโซม 22q13.2
- อัลลีลที่พบบ่อย
> *1 (ปกติ)
> *2 (ปกติ)
> *4 (ไม่ทำงาน)
> *5 (delete)
> *10 (ลด ~เอเชีย)
> *17 (ลด ~แอฟริกา)
> *1xN (เพิ่ม CN)
- Activity Score
> *1,*2 = 1.0  
> *4,*5 = 0.0  |  *10,*17 = 0.25 | 
> *1xN = 2.0+ (CN×1.0)
- Substrates หลัก (≥5 ชนิด)
> Codeine,
Tramadol,
Amitriptyline,
Nortriptyline,
Metoprolol,
Tamoxifen,
Risperidone,
Fluoxetine*,
Haloperidol,
Venlafaxine,
### **CYP2C19**
> โครโมโซม 10q23.33
- อัลลีลที่พบบ่อย
> *1 (ปกติ)
> *2 (ไม่ทำงาน)
> *3 (ไม่ทำงาน ~เอเชีย)
> *17 (เพิ่ม ~ผิวขาว)
- Activity Score
> *1 = 1.0  |  *2 = 0.5 | 
> *3 = 0.0 | *17 = 1.5
- Substrates หลัก (≥5 ชนิด)
>Clopidogrel (prodrug),
Omeprazole,
Esomeprazole,
Voriconazole,
Escitalopram,
Sertraline,
Diazepam,
Amitriptyline,
Proguanil,
> *Fluoxetine เป็นทั้ง substrate และ inhibitor ที่แรง
## Project: Draft CYP2C9 and CYP3A4/5 sections of the "Big 5" Cheat Sheet.
### **CYP2C9**
> โครโมโซม 10q23.33
- อัลลีลที่พบบ่อย
> *1 (ปกติ)
> *2 (ลด ~ผิวขาว 8-13%)
> *3 (ไม่ทำงาน ~ผิวขาว 6-10%)
> *5,*8,*11 (ลด ~แอฟริกา)
> *6 (ไม่ทำงาน)
- Activity Score
> *1 = 1.0  |  *2,*5,*8,*11 = 0.5 | 
> *3,*6 = 0.0 | 
- Substrates หลัก (≥5 ชนิด)
> Warfarin (S-enantiomer),
Phenytoin,
NSAIDs (Celecoxib, Ibuprofen),
Glipizide,
Losartan,
Fluvastatin,
Tolbutamide,
### **CYP3A4 / CYP3A5**
> โครโมโซม 7q22.1
- อัลลีลที่สำคัญ
> *1 (แสดงออก)
> *3 (ไม่แสดงออก ~ผิวขาว 85-90%)
> *6,*7 (~แอฟริกา)
- Tacrolimus & CYP3A5
> *1/*1 หรือ *1/*3: Expressors → ต้องการ dose สูง (ถึง 2×)
> *3/*3: Non-expressors → dose ต่ำ
- Substrates หลัก (≥5 ชนิด)
> Tacrolimus,
Cyclosporine,
Midazolam,
Simvastatin,
Atorvastatin,
Amlodipine,
Sildenafil,
Alprazolam,
Carbamazepine,
Testosterone,
Fentanyl,

>> แหล่งอ้างอิง: PharmVar (pharmvar.org) | CPIC Guidelines (cpicpgx.org) | PharmGKB (pharmgkb.org) | DPWG (knmp.nl) 

## Defense: Blank page test. Draw metabolic pathways and the Big 5 enzymes from memory.

<img width="1024" height="559" alt="metabolism" src="https://github.com/user-attachments/assets/fc8c52bd-b39e-4084-8e8a-774e61c4fc46" />

## Theory: Deep dive into Star Allele nomenclature and translation to phenotypes.
## Diplotype and Activity Score⭐
> คือ หัวใจสำคัญของวิชาเภสัชพันธุศาสตร์ (Pharmacogenomics) เพื่อใช้ทำนายว่าร่างกายของคนไข้จะจัดการกับยาอย่างไร
นี่คือสรุปขั้นตอนการวิเคราะห์จากระดับยีนไปจนถึงการออกฤทธิ์ของยา:
1. การเกิด Diplotype (Star Alleles)
มนุษย์เราได้รับยีนมาจากพ่อและแม่ฝั่งละหนึ่งข้าง เมื่อนำมารวมกันจะเรียกว่า Diplotype
    - Star Allele (*): คือชื่อเรียกรูปแบบของยีนที่กลายพันธุ์ (Variant) เช่น *1, *2, *3
    - ตัวอย่าง: ถ้าคุณได้รับยีนปกติ (*1) จากพ่อ และยีนที่ทำงานบกพร่อง (*2) จากแม่ คุณจะมี Diplotype เป็น *1/*2
  
2. นักวิทยาศาสตร์กำหนดคะแนนให้แต่ละ Allele ตามความสามารถในการทำงานของเอนไซม์ที่ยีนนั้นสร้างขึ้น ดังนี้:

| ระดับการทำงานของ Allele | คะแนน (Value) | ตัวอย่าง Allele |
| :---: | :---: | :---: |
| **Normal Function (ทำงานปกติ)** | 1.0 | "*1, *2 (ในบางเอนไซม์)" |
| **Decreased Function (ทำงานลดลง)** | 0.5 | "*10, *17, *41" |
| **No Function (ไม่ทำงานเลย)** | 0 | "*3, *4, *5, *6" |
- สูตรการคำนวณ: {Diplotype} = Score {Allele 1} + Score {Allele 2}
> ตัวอย่างการคำนวณ:
- คนที่มี Diplotype *1/*1 : $1 + 1 = 2.0$ (ทำงานเต็มประสิทธิภาพ)
- คนที่มี Diplotype *1/*4 : $1 + 0 = 1.0$ (ทำงานครึ่งเดียว)
- คนที่มี Diplotype *10/*10 : $0.5 + 0.5 = 1.0$ (ทำงานลดลง)
3. การทำนายฟีโนไทป์ (Phenotype Determination)
เมื่อได้คะแนนรวม (Total AS) แล้ว จะนำมาจัดกลุ่มคนไข้ (Phenotypes) เพื่อเลือกขนาดยา ดังนี้:

- **ตารางกำหนด Phenotype จาก Activity Score**


| กลุ่มฟีโนไทป์ (Phenotype) | AS (2D6) | AS (2C19) | AS (2C9) | ความหมาย |
| :--- | :--- | :--- | :--- | :--- |
| **Poor (PM)** | = 0 | = 0 | = 0 | **เอนไซม์ไม่ทำงานเลย** |
| **Intermediate Metabolizer (IM)** | >0 – 1.25 | 0.25–1.25* | 0.5–1.0* | **เอนไซม์ทำงานได้ปานกลาง/ค่อนข้างช้า** |
| **Normal (NM)** | 1.25–2.25 | 1.25–1.75* | 1.5–2.0 | **เอนไซม์ทำงานปกติ (ค่ามาตรฐาน)** |
| **Rapid (RM)** | N/A | 2.0–2.5* | N/A | **เอนไซม์ทำงานเร็ว** |
| **Ultrarapid (UM)** | > 2.25 | ≥ 3.0* | N/A | **เอนไซม์ทำงานเร็วผิดปกติ** |

- ทำไมเรื่องนี้ถึงสำคัญ?
ลองนึกถึงยา Codeine (ยาแก้ปวดที่ต้องเปลี่ยนเป็น Morphine โดย CYP2D6):
    - ถ้าคนไข้เป็น PM (AS = 0): กินยาไปเท่าไหร่ก็ไม่หายปวด เพราะร่างกายเปลี่ยนยาเป็น Morphine ไม่ได้
    - ถ้าคนไข้เป็น UM (AS > 2.25): ร่างกายจะเปลี่ยนยาเป็น Morphine เร็วและมากเกินไปจนอาจเกิดพิษ (กดการหายใจ) ได้แม้กินโดสปกติ
  
- สรุป: การรู้ Diplotype ช่วยให้หมอเลือก "ยาที่ใช่ ในขนาดที่ถูกต้อง" (Right drug, Right dose)

## Tools: PharmGKB database exploration. Map specific alleles to clinical outcomes.
## PharmGKB Gene-Drug Pairs & ผลลัพธ์ทางคลินิก
- ### 💊 CYP2C9 + Warfarin

### 📋 ข้อมูลภาพรวม (Overview)
* **ยีน (Gene):** `CYP2C9` (`*2` / `*3`)
* **ยา (Drug):** Warfarin
* **ระดับหลักฐาน (PharmGKB Evidence Level):** Level 1A (ระดับสูงสุด)
## 
---

### ⚠️ ความเสี่ยงและผลกระทบทางคลินิก (Clinical Risks)
> **ความเสี่ยงเลือดออกรุนแรง:** > อัลลีล `CYP2C9*3` จะทำให้การขจัดยา (Clearance) ของ *S-Warfarin* **ลดลงประมาณ 90%** ส่งผลให้ระดับยาในกระแสเลือดสูงขึ้นอย่างมีนัยสำคัญ ทำให้ค่า **INR สูงเกินช่วงการรักษา (Therapeutic Range)** และเพิ่มความเสี่ยงต่อการเกิด **ภาวะเลือดออกรุนแรง** เช่น เลือดออกในทางเดินอาหาร (GI bleed) หรือ เลือดออกในสมอง (Intracranial Hemorrhage)

---

### 💡 คำแนะนำในการปรับขนาดยา (CPIC Guidelines)

| ฟีโนไทป์ / แอลลีล | ผลกระทบต่อเอนไซม์ | คำแนะนำในการปรับขนาดรักษา (Maintenance Dose) | การติดตามอาการ |
| :--- | :--- | :--- | :--- |
| **CYP2C9\*2** | เอนไซม์ทำงานลดลงปานกลาง | **ลดขนาดยาลง 25 - 50%** | ติดตามค่า INR อย่างใกล้ชิดและบ่อยขึ้น |
| **CYP2C9\*3** | เอนไซม์ทำงานลดลงอย่างมาก | **ลดขนาดยาลง 50 - 75%** | ติดตามค่า INR อย่างใกล้ชิดและบ่อยขึ้น |

---

### 📄 เอกสารอ้างอิง (References)
* Johnson JA, et al. *Clinical Pharmacogenetics Implementation Consortium Guidelines for CYP2C9 and VKORC1 Genotypes and Warfarin Dosing.* **Clin Pharmacol Ther.** 2011.

##

- ### 🩸 CYP2C19 + Clopidogrel

### 📋 ข้อมูลภาพรวม (Overview)
* **ยีน (Gene):** `CYP2C19` (`*2` / `*3`)
* **ยา (Drug):** Clopidogrel
* **ระดับหลักฐาน (PharmGKB Evidence Level):** Level 1A (ระดับสูงสุด)

---

### ⚠️ ความเสี่ยงและผลกระทบทางคลินิก (Clinical Risks)
> **การลดฤทธิ์ต้านเกล็ดเลือด (Reduced Antiplatelet Effect):** > ผู้ป่วยที่เป็นกลุ่ม **Poor Metabolizer (PM)** และ **Intermediate Metabolizer (IM)** จะไม่สามารถเปลี่ยนยา Clopidogrel ซึ่งอยู่ในรูป Prodrug ให้กลายเป็นสารออกฤทธิ์ (Active Metabolite) ได้อย่างมีประสิทธิภาพ ส่งผลให้การยับยั้งเกล็ดเลือด (Platelet Inhibition) ลดลงอย่างมีนัยสำคัญ และเพิ่มความเสี่ยงต่อการเกิด **MACE (Major Adverse Cardiovascular Events) สูงขึ้นถึง 53%** *(อ้างอิงจากการวิเคราะห์ย่อยยาสูตร PLATO sub-analysis)*

---

### 💡 คำแนะนำทางคลินิก (CPIC Guidelines)

| ฟีโนไทป์ (Phenotype) | ผลกระทบทางคลินิก | คำแนะนำในการรักษา (Therapeutic Recommendation) |
| :--- | :--- | :--- |
| **Intermediate Metabolizer (IM)** | การสร้าง Active Metabolite ลดลง | พิจารณาปรับเปลี่ยนยา หรือเพิ่มการเฝ้าระวังอย่างใกล้ชิดตามดุลยพินิจแพทย์ |
| **Poor Metabolizer (PM)** | การสร้าง Active Metabolite ลดลงอย่างรุนแรง | **แนะนำให้เปลี่ยนไปใช้ยา Prasugrel หรือ Ticagrelor แทน** *(หากไม่มีข้อห้ามใช้ หรือ Contraindication)* |

---

### 📄 เอกสารอ้างอิง (References)
* Scott SA, et al. *Clinical Pharmacogenetics Implementation Consortium Guidelines for CYP2C19 Genotype and Clopidogrel Therapy.* **Clin Pharmacol Ther.** 2013.

## 

- ### 💊 CYP2D6 + Codeine

### 📋 ข้อมูลภาพรวม (Overview)
* **ยีน (Gene):** `CYP2D6` 
  * กลุ่มย่อย: `*4` / `*5` (Poor Metabolizer: PM) | `*1xN` (Ultrarapid Metabolizer: UM)
* **ยา (Drug):** Codeine
* **ระดับหลักฐาน (PharmGKB Evidence Level):** Level 1A (ระดับสูงสุด)

---

### ⚠️ ความเสี่ยงและผลกระทบทางคลินิก (Clinical Risks)

*   **กลุ่ม Poor Metabolizer (PM):** 
    > ยา Codeine จะ**ไม่ถูกเปลี่ยน**เป็นสารออกฤทธิ์หลักคือ Morphine ส่งผลให้ผู้ป่วย**ไม่ได้รับผลในการระงับปวดเลย (Lack of Efficacy)**
*   **กลุ่ม Ultrarapid Metabolizer (UM):** 
    > ยา Codeine จะถูกเปลี่ยนเป็น Morphine ในปริมาณที่**สูงมากอย่างรวดเร็วและผิดปกติ** ส่งผลให้เกิดพิษจากโอปิออยด์ขั้นรุนแรง เกิดภาวะ**กดการหายใจ (Respiratory Depression)** หัวใจหยุดเต้น และมีรายงานการเสียชีวิตในผู้ป่วยเด็ก

---

### 💡 คำแนะนำทางคลินิก (CPIC Guidelines)

| ฟีโนไทป์ (Phenotype) | ผลกระทบต่อระดับยา | คำแนะนำในการรักษา (Therapeutic Recommendation) |
| :--- | :--- | :--- |
| **Poor Metabolizer (PM)** | ไม่มี Morphine ในกระแสเลือด | **หลีกเลี่ยงการใช้ Codeine** และพิจารณาเปลี่ยนไปใช้ยากลุ่ม **Non-opioid analgesics** แทน |
| **Ultrarapid Metabolizer (UM)** | ระดับ Morphine สูงจนเป็นอันตราย | **หลีกเลี่ยงการใช้ Codeine** และหากจำเป็นต้องใช้ยากลุ่มโอปิออยด์ ให้เลือกใช้ **Opioid ที่ไม่ได้ทำงานผ่านเอนไซม์ CYP2D6** |

---

### 📄 เอกสารอ้างอิง (References)
* Crews KR, et al. *Clinical Pharmacogenetics Implementation Consortium Guidelines for CYP2D6 Genotype and Codeine Therapy: 2014 Update.* **Clin Pharmacol Ther.** 2014.

## 

- ###  🍄CYP2C19 + Voriconazole

### 📋 ข้อมูลภาพรวม (Overview)
* **ยีน (Gene):** `CYP2C19` 
  * กลุ่มย่อย: `*2` / `*3` (Poor Metabolizer: PM) | (Ultrarapid Metabolizer: UM)
* **ยา (Drug):** Voriconazole (ยาต้านเชื้อรา)
* **ระดับหลักฐาน (PharmGKB Evidence Level):** Level 1A (ระดับสูงสุด)

---

### ⚠️ ความเสี่ยงและผลกระทบทางคลินิก (Clinical Risks)

*   **กลุ่ม Poor Metabolizer (PM):** 
    > **ความเสี่ยงต่อพิษจากยา (Toxicity Risk):** ผู้ป่วยกลุ่มนี้จะมีระดับยา Voriconazole ในกระแสเลือด**สูงขึ้นประมาณ 4 เท่า (4×)** ซึ่งเพิ่มความเสี่ยงต่อการเกิดพิษอย่างรุนแรง ได้แก่ อาการผิดปกติทางการมองเห็น (Visual Disturbances), พิษต่อตับ (Hepatotoxicity) และพิษต่อระบบประสาท (Neurotoxicity)
*   **กลุ่ม Ultrarapid Metabolizer (UM):** 
    > **ความเสี่ยงต่อความล้มเหลวในการรักษา:** เอนไซม์ที่ทำงานเร็วเกินไปจะทำให้ระดับยาในเลือด**ต่ำกว่าเกณฑ์มาตรฐาน** ส่งผลให้เกิดความล้มเหลวในการรักษา (Treatment Failure) โดยเฉพาะในการรักษาโรคติดเชื้อราแอสเปอร์จิลลัสชนิดลุกลาม (Invasive Aspergillosis) ซึ่งเป็นอันตรายถึงชีวิต

---

### 💡 คำแนะนำทางคลินิก (Clinical Guidelines)

| ฟีโนไทป์ (Phenotype) | ผลกระทบต่อระดับยา | คำแนะนำในการรักษา (Therapeutic Recommendation) |
| :--- | :--- | :--- |
| **Poor Metabolizer (PM)** | ระดับยาสูงขึ้นอย่างรุนแรง (~4×) | **พิจารณาลดขนาดยา (Dose Reduction)** ลงอย่างเหมาะสม และติดตามระดับยาในเลือด (TDM) อย่างใกล้ชิด |
| **Ultrarapid Metabolizer (UM)** | ระดับยาต่ำเกินไปจนไม่ได้ผล | **พิจารณาหลีกเลี่ยง Voriconazole** และเปลี่ยนไปใช้ยาต้านเชื้อรากลุ่มอื่นทดแทน เช่น **Isavuconazole** |

---

### 📄 เอกสารอ้างอิง (References)
* Moriyama B, et al. *Clinical Pharmacogenetics Implementation Consortium Guidelines for CYP2C19 Genotype and Voriconazole Therapy.* **Clin Pharmacol Ther.** 2017.

## 

- ### 🫘  CYP3A5 + Tacrolimus

### 📋 ข้อมูลภาพรวม (Overview)
* **ยีน (Gene):** `CYP3A5` (`*1` Expresser / `*3` Non-expresser)
* **ยา (Drug):** Tacrolimus (ยากดภูมิคุ้มกัน)
* **ระดับหลักฐาน (PharmGKB Evidence Level):** Level 1A (ระดับสูงสุด)

---

### ⚠️ ความเสี่ยงและผลกระทบทางคลินิก (Clinical Risks)
> **ความเสี่ยงต่อการปฏิเสธอวัยวะ (Risk of Allograft Rejection):** > ผู้ป่วยกลุ่ม **Expresser (ผู้ที่มีแอลลีล `*1`)** จะมีการแสดงออกของเอนไซม์อย่างเต็มที่ ส่งผลให้การขจัดยา Tacrolimus (Clearance) เกิดขึ้น**สูงและรวดเร็วมาก** ทำให้ระดับยาในกระแสเลือดต่ำกว่าเกณฑ์การรักษา (Sub-therapeutic Levels) ซึ่งเพิ่มความเสี่ยงอย่างรุนแรงต่อการเกิดภาวะร่างกายปฏิเสธอวัยวะที่ปลูกถ่าย (Allograft Rejection)

📌 **หมายเหตุสำคัญ (Special Note):** ในกรณีของการผ่าตัด**ปลูกถ่ายตับ (Liver Transplantation)** ฟีโนไทป์ของยีนในตัวผู้บริจาคอวัยวะ (**Donor Genotype**) จะมีผลต่อการเผาผลาญและการทำลายยาในร่างกายของผู้ป่วยร่วมด้วย

---

### 💡 คำแนะนำทางคลินิก (CPIC Guidelines)

| ฟีโนไทป์ (Phenotype) | ผลกระทบต่อระดับยา | คำแนะนำในการรักษา (Therapeutic Recommendation) |
| :--- | :--- | :--- |
| **CYP3A5 Expresser** <br> (มีแอลลีล `*1`) | ระดับยาต่ำกว่าเกณฑ์การรักษาอย่างรวดเร็ว | **แนะนำให้เริ่มยา (Starting Dose) สูงเป็น 1.5 - 2 เท่า** ของขนาดมาตรฐาน และต้องติดตามระดับยาในเลือดตอนระดับต่ำสุด (**Trough Level: C0**) อย่างใกล้ชิด |
| **CYP3A5 Non-expresser** <br> (เช่น `*3/*3`) | การเผาผลาญยาปกติ/ช้า | เริ่มให้ยาในขนาดมาตรฐานตามปกติ (Standard Dosing) |

---

### 📄 เอกสารอ้างอิง (References)
* Birdwell KA, et al. *Clinical Pharmacogenetics Implementation Consortium Guidelines for CYP3A5 Genotype and Tacrolimus Dosing.* **Clin Pharmacol Ther.** 2015.

## Simulation: Practice translating raw genetic sequences (e.g., *1/*4) into metabolic statuses.




## population frequencies for major variants.
## ความชุกของตัวแปรหลักในเชื้อชาติต่างๆ

| Allele | Function | Frequency European | Frequency South Asian | Frequency East Asian | Frequency African American | 
| :--- | :--- | :---: | :---: | :---: | :---: |
| CYP2D6*4 | No function | 18.48476 | 8.9567736 | 52.69325 | 4.8111428 |
| CYP2D6*10 | Decreased Function | 1.571283 | 7.559443 | 42.84454 | 3.8160447 |
| CYP2C19*2 | No function | 14.685704 | 26.9916 | 28.352264 | 18.149492 |
| CYP2C19*17 | Increased function | 21.54386 | 17.077276 | 2.0541333| 20.72274 
| CYP2C9*2 | Decreased Function | 12.73007 | 11.379695 | 0.21256818 | 2.243724 |
| CYP2C9*3 | No function | 7.554484 | 10.985958 | 3.7616692 | 1.350592 |
| CYP3A5*1 | Expressors | 7.410407 | 32.672024 | 25.355196 | 45.28548 |
| CYP3A5*3 | Non-expressors | 92.43815 | 67.327976 | 74.57923 | 31.597915 |

คำอธิบายกลุ่มชาติพันธุ์ทั้ง 4 กลุ่มตามมาตรฐานของ CPIC/PharmGKB แบบสั้นๆ:

- European (ประชากรยุโรป): กลุ่มคนผิวขาวทั้งหมด รวมถึงประชากรในทวีปยุโรป อเมริกาเหนือ (ที่สืบเชื้อสายมาจากยุโรป) และออสเตรเลีย

- South Asian (ประชากรเอเชียใต้): กลุ่มคนในแถบอนุทวีปอินเดีย เช่น อินเดีย ปากีสถาน บังกลาเทศ ศรีลังกา และเนปาล

- East Asian (ประชากรเอเชียตะวันออก): กลุ่มคนเอเชียผิวเหลือง รวมถึงไทย จีน ญี่ปุ่น เกาหลี และประเทศในแถบอาเซียน (เอเชียตะวันออกเฉียงใต้) ทั้งหมด

- African American (ประชากรแอฟริกัน-อเมริกัน): กลุ่มคนผิวดำในประเทศสหรัฐอเมริกา ซึ่งมีพันธุกรรมผสมผสานระหว่างแอฟริกาดั้งเดิมและกลุ่มอื่นในอเมริกา
  
### 📄 อ้างอิง (References)

อ้างอิงตัวเลขความถี่จาก CPIC Frequency Table ปีล่าสุด

## Theory: Study specific drug classes impacted by the Big 5 (Opioids, SSRIs, PPIs).

1. **กลุ่มยาแก้ปวดโอปิออยด์ (Opioids)**
   
การออกฤทธิ์ทางคลินิกของยาโอปิออยด์ขึ้นอยู่กับความสมดุลระหว่าง "การเปลี่ยนยาให้พร้อมออกฤทธิ์ (Prodrug Activation)" และ "การขับยาออกจากร่างกาย (Drug Clearance)"

- เอนไซม์หลักที่เกี่ยวข้อง: **CYP2D6** (ทางหลักในการเปลี่ยนรูปยา), **CYP3A4/5** (ทางหลักในการขับทำลายยา)

- กลไกทางเภสัชวิทยา: ยาแก้ปวดจำพวก Codeine และ Tramadol จัดเป็นยาในรูปแบบยังไม่ออกฤทธิ์ (Prodrug) ตัวมันเองไม่มีฤทธิ์แก้ปวด แต่ต้องพึ่งพาเอนไซม์ CYP2D6 ในการตัดแต่งโมเลกุลให้กลายเป็นสารออกฤทธิ์เด่นที่จับกับตัวรับในสมองได้ดี ได้แก่ Morphine (จาก Codeine) และ O-desmethyltramadol (จาก Tramadol) ในขณะที่ CYP3A4 จะทำหน้าที่เปลี่ยนยาเหล่านี้ไปเป็นสารที่ไม่ออกฤทธิ์เพื่อขับทิ้ง

ผลกระทบแยกตามฟีโนไทป์:

**กลุ่ม Ultrarapid Metabolizer (UM)**: เอนไซม์ CYP2D6 ทำงานเร็วและแรงกว่าปกติมาก ส่งผลให้ยาเปลี่ยนสภาพเป็นมอร์ฟีนในปริมาณมหาศาลและเฉียบพลันในกระแสเลือด นำไปสู่ภาวะ "กดการหายใจขั้นรุนแรงจนถึงแก่ชีวิต (Fatal Respiratory Depression)"

**กลุ่ม Poor Metabolizer (PM)**: ร่างกายแทบไม่มีเอนไซม์ทำงาน ส่งผลให้ไม่เกิดการเปลี่ยนรูปยา คนไข้จะ "ไม่หายปวดเลย (Therapeutic Failure)" ซึ่งอันตรายมากเพราะคนไข้อาจตัดสินใจกินยาเพิ่มเองจนเกิดพิษจากตัวยาตั้งต้นสะสม

- ข้อบังคับความปลอดภัย (Safety Mandates): องค์การอาหารและยาแห่งสหรัฐอเมริกา (US FDA) บังคับใส่ Boxed Warning ห้ามใช้ยา Codeine และ Tramadol ในเด็กอายุต่ำกว่า 12 ปี, เด็กอายุต่ำกว่า 18 ปีหลังผ่าตัดต่อมทอนซิล/อดีนอยด์ และสตรีให้นมบุตร (เนื่องจากมอร์ฟีนที่เข้มข้นจะผ่านน้ำนมไปหยุดการหายใจของทารกได้)

📚 แหล่งอ้างอิงมาตรฐาน: 
> FDA Drug Safety Communication (April 20, 2017): FDA restricts use of prescription codeine and tramadol medicines in children.

> CPIC Guideline for CYP2D6 and Opioid Therapy (Crews et al., Clinical Pharmacology & Therapeutics).

2. **กลุ่มยาต้านเศร้ากลุ่ม SSRIs** (Selective Serotonin Reuptake Inhibitors)
   
ยารักษาโรคซึมเศร้าและวิตกกังวลกลุ่ม SSRIs เป็นหนึ่งในสาเหตุหลักที่จิตแพทย์มักต้องใช้วิธีสุ่มลองยา (Trial-and-Error) เนื่องจากพันธุกรรมของผู้ป่วยแต่ละคนสลายยาได้ไม่เท่ากัน

- เอนไซม์หลักที่เกี่ยวข้อง: **CYP2C19** (คุมยา Escitalopram, Citalopram, Sertraline), **CYP2D6** (คุมยา Fluoxetine, Paroxetine)

- กลไกทางเภสัชวิทยา: แตกต่างจากกลุ่มโอปิออยด์ ยา SSRIs ถูกจ่ายในรูปแบบ "ออกฤทธิ์ทันที (Active Drug)" ดังนั้น เอนไซม์กลุ่ม Big Five จึงทำหน้าที่ในทางตรงกันข้ามคือ "ทำลายและขับยาออกจากร่างกาย (Drug Inactivation & Clearance)"

ผลกระทบแยกตามฟีโนไทป์:

**กลุ่ม Poor Metabolizer (PM)**: ขาดเอนไซม์ในการทำลายยา ส่งผลให้ปริมาณยาต้านเศร้าสะสมในกระแสเลือดพุ่งสูงขึ้นกว่าคนปกติถึง 3 เท่าตัว ก่อให้เกิดอาการข้างเคียงที่รุนแรงและเป็นอันตรายต่อชีวิต เช่น "คลื่นไฟฟ้าหัวใจผิดปกติ (QT Interval Prolongation)" ซึ่งนำไปสู่หัวใจเต้นผิดจังหวะเฉียบพลัน, อาการกลุ่มอาการเซโรโทนินล้น (Serotonin Syndrome) และผลข้างเคียงต่อระบบทางเดินอาหารจนคนไข้ทนยาไม่ได้

**กลุ่ม Ultrarapid Metabolizer (UM)**: เอนไซม์ทำลายยาต้านเศร้าทิ้งทันทีที่กลืนลงไป ระดับยาในเลือดและสมองต่ำกว่าเกณฑ์การรักษาตลอดเวลา ส่งผลให้ "การรักษาล้มเหลวอย่างสิ้นเชิง (Therapeutic Failure)" คนไข้อาจเกิดภาวะดิ่งหรือกลับมาคิดสั้นซ้ำ

- ข้อบังคับความปลอดภัย (Safety Mandates): US FDA ออกข้อบังคับจำกัดขนาดยาใช้งานสูงสุดของ Citalopram ไว้ห้ามเกิน 20 mg/day (จากโดสปกติ 40 mg) ในผู้ป่วยที่เป็นกลุ่ม CYP2C19 PM เพื่อป้องกันพิษต่อหัวใจ

📚 แหล่งอ้างอิงมาตรฐาน:

> FDA Drug Safety Communication (August 24, 2011): Abnormal heart rhythms associated with high doses of Celexa (citalopram hydrobromide).

> CPIC Guideline for CYP2D6 and CYP2C19 Genotypes and Selective Serotonin Reuptake Inhibitor Dosing (Hicks et al., Clinical Pharmacology & > Therapeutics).

3.**กลุ่มยาลดกรด PPIs** (Proton Pump Inhibitors)

ยาลดกรดกลุ่ม PPIs (เช่น Omeprazole, Lansoprazole, Pantoprazole) เป็นยาพื้นฐานที่ใช้กันแพร่หลายในโรคแผลในกระเพาะอาหารและกรดไหลย้อน (GERD)

- เอนไซม์หลักที่เกี่ยวข้อง: CYP2C19 (ทางหลัก รับผิดชอบการสลายยามากกว่า 80%), CYP3A4 (ทางสำรอง)

- กลไกทางเภสัชวิทยา: ยา PPIs ถูกจ่ายในรูปแบบ "ออกฤทธิ์ทันที (Active Drug)" และอาศัย CYP2C19 ในการทำลายยาเช่นเดียวกับ SSRIs แต่กลุ่มยานี้มีลักษณะพิเศษทางคลินิกที่ความบกพร่องของยีนสามารถนำมาใช้เป็นประโยชน์ในการรักษาได้

ผลกระทบแยกตามฟีโนไทป์:

**กลุ่ม Poor Metabolizer (PM)**: ยีนบกพร่องทำให้สลายยาลดกรดไม่ได้ ยาจึงหมุนเวียนอยู่ในร่างกายยาวนานขึ้น ส่งผลให้กระเพาะอาหารมีความเป็นกรดต่ำ (pH สูง) ได้ยาวนานกว่าปกติ ในแง่การรักษาโรคแผลในกระเพาะรุนแรง หรือการฆ่าเชื้อ H. pylori "ผู้ป่วยกลุ่ม PM จะมีอัตราการหายจากโรคสูงที่สุดอย่างมีนัยสำคัญ" (แต่ต้องระวังผลเสียระยะยาวหากกินต่อเนื่อง เช่น กระดูกพรุน หรือแมกนีเซียมในเลือดต่ำ)

**กลุ่ม Ultrarapid Metabolizer (UM)**: ร่างกายสลายยาลดกรดทิ้งเร็วเกินไป กรดในกระเพาะจึงไม่ลดลง นำไปสู่ภาวะ "โรคกรดไหลย้อนดื้อยา (Refractory GERD) หรือแผลในกระเพาะไม่ยอมหาย"

- แนวทางจัดการความปลอดภัย: แนวทางเวชปฏิบัติของ CPIC แนะนำให้แพทย์ "เพิ่มขนาดยาพุ่งสูงขึ้น 50% - 100%" ในผู้ป่วยกลุ่ม UM หรือปรับเปลี่ยนไปใช้ยา Rabeprazole แทน เนื่องจากยาตัวนี้ถูกขับออกผ่านกระบวนการที่ไม่ได้ใช้เอนไซม์ (Non-enzymatic pathway) เป็นหลัก จึงปลอดภัยจากความผันผวนทางพันธุกรรมของ CYP2C19

📚 แหล่งอ้างอิงมาตรฐาน:

CPIC Guideline for CYP2C19 and Proton Pump Inhibitor Dosing (Lima et al., Clinical Pharmacology & Therapeutics).

U.S. Food & Drug Administration (FDA): PRILOSEC (omeprazole) clinical pharmacology label insights.

## Tools: Advanced PharmVar queries. Identify ultra-rare alleles vs. common variants.

🧬 1.**อัลลีล "Star" ทั่วไป (Core Star Alleles หรือ Sequence Variants)**

ตามนิยามของ PharmVar อัลลีลกลุ่มนี้คือ "ยีนที่มีความยาวปกติและจำนวนชุด (Copy Number) เท่ากับคนปกติ แต่อักษรหรือลำดับเบสภายในสาย DNA เกิดความผิดปกติ"

กลไกทางพันธุศาสตร์: เกิดจากปฏิกิริยา SNV (Single Nucleotide Variant) หรือความแปรปรวนระดับเบสเดี่ยว รวมถึงการขาดหายหรือเพิ่มขึ้นของเบสขนาดเล็กมาก (Small Indels) ภายในบริเวณ Exon หรือ Intron ของยีน

- ตัวอย่างสำคัญตามฐานข้อมูล PharmVar:

**CYP2D6*2 (Normal Function)**: มีการเปลี่ยนแปลงของลำดับเบสที่ส่งผลให้กรดอะมิโนเปลี่ยนตำแหน่ง (เช่น 2850C>T) แต่โครงสร้างโดยรวมยังทำงานได้ดีเท่าคนปกติ

**CYP2D6*10 (Decreased Function)**: เกิดจากเบสเปลี่ยนจุดเดียว (100C>T) ทำให้โปรตีนที่สร้างขึ้นมาไม่เสถียรและทำงานลดลงอย่างมาก (เป็นอัลลีลที่พบบ่อยที่สุดในประชากรไทยและเอเชีย)

**CYP2D6*4 (No Function)**: เกิดการเปลี่ยนเบสตรงบริเวณรอยต่อในการตัดแต่งยีน (1846G>A) ส่งผลให้กระบวนการ Splicing ล้มเหลว เอนไซม์ที่สร้างขึ้นมาจึงใช้งานไม่ได้เลย

🧬 2. **ตัวแปรโครงสร้างที่หายากมาก (Structural Variants - SVs)**

นี่คือกลุ่มที่เป็นความท้าทายสูงสุดในระบบของ PharmVar เพราะโครงสร้างของยีนเปลี่ยนไปในระดับมหภาค (Large-scale Genomic Alterations) ไม่ใช่แค่เบสเปลี่ยนจุดเดียว ยีนอาจจะยาวไม่เท่าเดิม หรือมีจำนวนซ้ำที่ไม่ปกติ (Copy Number Variation - CNV) ซึ่ง PharmVar

จัดหมวดหมู่ไว้ 3 รูปแบบหลัก:

A. **การขาดหายไปของยีนทั้งชุด (Whole-Gene Deletion)**

- เช่น CYP2D6*5

- กลไก: เกิดจากความผิดพลาดขณะแบ่งเซลล์ (Homologous Recombination) ทำให้ยีน CYP2D6 หลุดหายไปทั้งยีนจากโครโมโซมเส้นนั้น เหลือทิ้งไว้เพียงยีนหลอก (Pseudogenes) อย่าง CYP2D7 และ CYP2D8 ที่อยู่ข้างเคียงเท่านั้น

- ผลกระทบ: ร่างกายไม่สามารถผลิตเอนไซม์ CYP2D6 จากโครโมโซมข้างนั้นได้เลย (No Function)

B. **การเพิ่มจำนวนชุดยีน (Gene Duplication / Multiplication)**

- จะเขียนระบุตัวเลขจำนวนชุดต่อท้ายด้วย xN (เช่น *1x2, *2x2, *4x2)

- กลไก: มีการสำเนายีนซ้ำขึ้นมาลอยอยู่บนโครโมโซมเส้นเดียวกัน ทำให้คนไข้หนึ่งคนมียีนตัวนี้ 2 ชุด, 3 ชุด หรือมากกว่านั้นในโครโมโซมข้างเดียว

- ผลกระทบวิกฤต: * หากยีนที่ซ้ำเป็นยีนปกติ (เช่น *1x2 หรือ *2x2) ตับจะผลิตเอนไซม์ออกมาปริมาณมหาศาล กลายเป็นฟีโนไทป์ Ultrarapid Metabolizer (UM) เสี่ยงพิษเฉียบพลันจากยา Prodrug เช่น Codeine

หากยีนที่ซ้ำเป็นยีนที่ไม่ทำงานอยู่แล้ว (เช่น *4x2) แม้จะมีหลายชุดในโครโมโซม ร่างกายก็ยังคงสลายยาไม่ได้เช่นเดิม (No Function)

C. **ยีนลูกผสม / ไฮบริด (Hybrid / Chimeric Genes)**

- เช่น CYP2D6*36, CYP2D6*13 หรือโครงสร้างซับซ้อนอย่าง CYP2D6*36-*10

- กลไก: เนื่องจากยีนจริง CYP2D6 วางตัวอยู่ใกล้กับยีนหลอก CYP2D7 ซึ่งมีลำดับเบสคล้ายกันมาก โครโมโซมจึงเกิดการสลับชิ้นส่วนแบบไขว้ข้าม (Unequal Crossover) เอาชิ้นส่วนท่อนหัวของยีนหนึ่งมาต่อกับท่อนหางของอีกยีนหนึ่ง

- ผลกระทบ: โครงสร้างที่ผิดรูปนี้มักส่งผลให้เอนไซม์สูญเสียการทำงาน (No Function) เช่น CYP2D6*36 ที่รับชิ้นส่วน Exon 9 มาจากยีนหลอกทำให้เอนไซม์ไม่ทำงาน

 📊 ตารางสรุปข้อแตกต่าง (Key Comparison)
 
| การเปรียบเทียบ | อัลลีล Star ทั่วไป (Core Star Alleles) | ตัวแปรโครงสร้าง (Structural Variants - SVs) | 
| :--- | :--- | :--- |
| ขนาดความผิดปกติ | ระดับจุด (Micro-variation: SNVs, Small Indels) |ระดับโครงสร้างยีน/โครโมโซม (Macro-variation: CNVs) |
| ความยาวของยีน | ความยาวและจำนวนยีนปกติเท่าเดิม | ยีนหลุดหายไปทั้งชุด, เพิ่มจำนวนชุด, หรือสลับท่อนยีน | 
| การตั้งชื่อระบบ PharmVar | ระบุเป็นตัวเลขโดด ๆ เช่น *2, *4, *10 | ระบุเป็น *5 (Deletion), มีตัวต่อท้าย xN, หรือชื่อลูกผสม |
| ความชุกในประชากร | สูงมาก (พบได้ทั่วไปในระดับเปอร์เซ็นต์ในทุกชาติพันธุ์)| ต่ำมาก (มักน้อยกว่า 1% หรือจำเพาะในบางตระกูล) | 
| ข้อจำกัดในห้องปฏิบัติการ | ไม่มี ตรวจพบได้ง่ายด้วยวิธีมาตรฐานทั่วไป เช่น PCR | สูงมาก ชุดตรวจ PCR ทั่วไปจะ "มองไม่เห็น (Blind Spot)" เนื่องจากเครื่องจะอ่านผลว่าปกติ ทั้งที่จริง ๆ คนไข้มียีนซ้ำหลายชุด หรือมียีนลูกผสมซ่อนอยู่ ต้องใช้เทคนิคเฉพาะอย่าง MLPA หรือ Long-read sequencing ในการตรวจหาจำนวนชุดยีนที่แท้จริง|

อ้างอิง

https://www.pharmvar.org/gene-support/Variation_CYP2D6.pdf

## Simulation: Mock patient cases: Opioid metabolism in Ultra-rapid vs. Poor metabolizers.
### สถานการณ์จำลองผู้ป่วย (Mock Patient Cases) เพื่อแสดงให้เห็นความแตกต่างทางคลินิกของการเมแทบอลิซึมยาแก้ปวดกลุ่มโอปิออยด์ (Opioids) ระหว่างผู้ป่วยกลุ่ม Ultrarapid Metabolizer (UM) และ Poor Metabolizer (PM)

    🏥 เคสจำลองที่ 1: ผู้ป่วยกลุ่ม Ultrarapid Metabolizer (UM) ของยีน CYP2D6
    
    📝 ข้อมูลผู้ป่วย (Patient Profile)
    
    ผู้ป่วย: เด็กชายอายุ 6 ปี เข้ารับการผ่าตัดต่อมทอนซิลและต่อมอดีนอยด์ (Tonsillectomy & Adenoidectomy) เนื่องจากภาวะทางเดินหายใจอุดกั้นขณะหลับ (Obstructive Sleep Apnea)

    การสั่งใช้ยา: หลังผ่าตัด แพทย์สั่งจ่ายยาแก้ปวดน้ำเชื่อม Codeine phosphate ขนาดมาตรฐานตามน้ำหนักตัวเพื่อระงับอาการปวดแผลที่บ้าน

    ผลตรวจทางเภสัชพันธุศาสตร์ (ตรวจย้อนหลัง): จีโนไทป์ CYP2D6 *1/*1x2 (มียีนปกติซ้ำกัน 2 ชุดบนโครโมโซมฝั่งเดียว) ➔ ฟีโนไทป์: **Ultrarapid Metabolizer (UM)**

    🚨 เหตุการณ์ทางคลินิก (Clinical Course)
    
    หลังจากกลับไปพักฟื้นที่บ้านและได้รับยา Codeine ไปเพียง 2 โดส ในคืนนั้นมารดาพบว่าเด็กมีอาการซึมมาก ปลุกตื่นยาก หายใจช้าและมีเสียงครืดคราดอย่างรุนแรง จึงรีบนำส่งห้องฉุกเฉิน

    สัญญาณชีพที่ห้องฉุกเฉิน : อัตราการหายใจช้าวิกฤต (8 ครั้ง/นาที), รูม่านตาหดเล็กเท่ารูเข็ม (Pinpoint pupils), ความอิ่มตัวของออกซิเจนในเลือดลดต่ำลง (SpO2 84%)

    การวินิจฉัย: ภาวะพิษจากมอร์ฟีนเฉียบพลัน (Acute Morphine Toxicity) เนื่องจากการเปลี่ยนรูปยาที่เร็วเกินไปจากภาวะยีนไวเกิน

    🛠️ การแก้ไขและการจัดการทางคลินิก (Clinical Management)
    
    การช่วยชีวิตเฉียบพลัน : แพทย์ทำการฉีดยาต้านโอปิออยด์ Naloxone (IV) ทันที เพื่อแย่งจับกับตัวรับในสมอง ช่วยกู้สัญญาณชีพและการหายใจของเด็กให้กลับคืนมา

    การปรับเปลี่ยนยาตามแนวทาง CPIC : ห้ามใช้ ยา Codeine หรือ Tramadol ในผู้ป่วยรายนี้เด็ดขาด โดยให้เปลี่ยนไปใช้ยาแก้ปวดกลุ่มอื่นที่ไม่พึ่งพาเอนไซม์ CYP2D6 เช่น Non-steroidal anti-inflammatory drugs (NSAIDs) 
    หรือ Acetaminophen  หรือหากจำเป็นต้องใช้ยาโอปิออยด์กลุ่มรุนแรง ให้พิจารณาใช้ Morphine (ในขนาดยาที่ต่ำกว่าปกติและมอนิเตอร์อย่างใกล้ชิด) หรือ Fentanyl แทน


    🏥 เคสจำลองที่ 2: ผู้ป่วยกลุ่ม Poor Metabolizer (PM) ของยีน CYP2D6
    
    📝 ข้อมูลผู้ป่วย (Patient Profile)
    
    ผู้ป่วย: หญิงอายุ 45 ปี ประสบอุบัติเหตุหกล้ม ส่งผลให้มีกระดูกข้อมือร้าว (Distal radius fracture) ใส่เฝือกชั่วคราว

    การสั่งใช้ยา: แพทย์สั่งจ่ายยาแก้ปวดชนิดเม็ดสูตรผสม Tramadol / Acetaminophen เพื่อควบคุมอาการปวดระดับปานกลางถึงรุนแรง (Moderate to Severe Pain)

    ผลตรวจทางเภสัชพันธุศาสตร์ (ตรวจย้อนหลัง): จีโนไทป์ CYP2D6 *4/*4 (ยีนบกพร่องชนิด No Function ทั้งสองข้าง) ➔ ฟีโนไทป์: Poor Metabolizer (PM)

    🚨 เหตุการณ์ทางคลินิก (Clinical Course)
    
    ผู้ป่วยรับประทานยาตามแพทย์สั่งอย่างเคร่งครัด แต่หลังจากผ่านไป 24 ชั่วโมง ผู้ป่วยโทรกลับมาแจ้งที่โรงพยาบาลว่า "ยาไม่ได้ผลเลย" อาการปวดข้อมือยังคงรุนแรงเท่าเดิม (Pain Score 9/10) 
    จนทำให้นอนไม่หลับ ตลอดจนมีอาการคลื่นไส้และเวียนศีรษะร่วมด้วย

    สาเหตุทางเภสัชวิทยา: เนื่องจากยีนบกพร่อง ร่างกายของผู้ป่วยจึงไม่สามารถเปลี่ยนยา Tramadol (Prodrug) ให้กลายเป็นสารออกฤทธิ์หลัก (O-desmethyltramadol) ได้เลย ทำให้ไม่มีฤทธิ์ระงับปวด 
    มีเพียงตัวยาตั้งต้นที่ไม่ได้แปลงสภาพสะสมอยู่ ซึ่งส่งผลให้เกิดอาการข้างเคียงอย่างคลื่นไส้ เวียนศีรษะ แต่ไม่ช่วยลดความเจ็บปวด

    🛠️ การแก้ไขและการจัดการทางคลินิก (Clinical Management)
    
    การปรับเปลี่ยนยาตามแนวทาง CPIC: แนวทางเวชปฏิบัติระบุชัดเจนว่ากลุ่ม CYP2D6 PM จะไม่มีการตอบสนองต่อยา Tramadol และ Codeine แพทย์จึงสั่ง หยุดใช้ยา Tramadol ทันที 
    เนื่องจากกินไปก็ไม่ได้ผลและเพิ่มความเสี่ยงต่ออาการข้างเคียง

    ยาทางเลือก: เปลี่ยนไปใช้ยาในกลุ่มที่ไม่ต้องผ่านการกระตุ้นด้วย CYP2D6 เช่น Hydrocodone หรือ Oxycodone (แม้จะผ่าน CYP2D6 บ้าง แต่ตัวยาตั้งต้นมีฤทธิ์แก้ปวดในตัวเองอยู่แล้ว) 
    หรือเปลี่ยนไปใช้กลุ่มยาที่ตัดขั้นตอนการเผาผลาญที่ตับออกไปเลยอย่าง Morphine หรือยากลุ่ม NSAIDs ชนิดแรง เพื่อระงับอาการปวดอย่างมีประสิทธิภาพ


📚 เอกสารอ้างอิงระดับสากล (Clinical Citations)

> Clinical Pharmacogenetics Implementation Consortium (CPIC): > Crews, K. R., et al. "Clinical Pharmacogenetics Implementation Consortium (CPIC) Guideline for CYP2D6 and Opioid Therapy." Clinical Pharmacology & Therapeutics. ไกด์ไลน์นี้ให้คำแนะนำระดับสูงสุด (Strong Recommendation) ว่ากลุ่ม UM ให้หลีกเลี่ยงการใช้ Codeine/Tramadol เนื่องจากเสี่ยงต่อพิษร้ายแรง และกลุ่ม PM ให้หลีกเลี่ยงเนื่องจากยาจะไม่ได้ผลทางคลินิก

> U.S. Food and Drug Administration (US FDA) Boxed Warning:

> FDA Drug Safety Communication (2017): "FDA restricts use of prescription codeine and tramadol medicines in children; recommends against use in breastfeeding women." ข้อบังคับข้อห้ามใช้ (Contraindication) อันเป็นผลมาจากกรณีศึกษาผู้ป่วยเด็กกลุ่ม CYP2D6 UM ที่เกิดภาวะทางเดินหายใจถูกกดจนเสียชีวิตหลังการผ่าตัดทอนซิล

คลังข้อมูลดิจิทัลและรหัสพันธุกรรม:

> ข้อมูลรหัสโครงสร้างตัวแปรยีนซ้ำชุด (xN) อ้างอิงมาตรฐานจาก PharmVar (Pharmacogene Variation Consortium) ในหัวข้อ CYP2D6 Gene Structural Variants Table และระบบฐานข้อมูลกลาง ClinPGx (clinpgx.org)
