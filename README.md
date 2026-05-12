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

| คะแนนรวม (Total AS) | กลุ่มฟีโนไทป์ (Phenotype) | ความหมาย |
| :--- | :--- | :--- |
| **AS > 2.25** | **Ultra-rapid Metabolizer (UM)** | เอนไซม์ทำงานเร็วมากผิดปกติ |
| **AS = 1.25 ถึง 2.25** | **Normal Metabolizer (NM)** | เอนไซม์ทำงานปกติ (ค่ามาตรฐาน) |
| **AS = 0.25 ถึง 1.0** | **Intermediate Metabolizer (IM)** | เอนไซม์ทำงานได้ปานกลาง/ค่อนข้างช้า |
| **AS = 0** | **Poor Metabolizer (PM)** | เอนไซม์ไม่ทำงานเลย |\

- ทำไมเรื่องนี้ถึงสำคัญ?
ลองนึกถึงยา Codeine (ยาแก้ปวดที่ต้องเปลี่ยนเป็น Morphine โดย CYP2D6):
    - ถ้าคนไข้เป็น PM (AS = 0): กินยาไปเท่าไหร่ก็ไม่หายปวด เพราะร่างกายเปลี่ยนยาเป็น Morphine ไม่ได้
    - ถ้าคนไข้เป็น UM (AS > 2.25): ร่างกายจะเปลี่ยนยาเป็น Morphine เร็วและมากเกินไปจนอาจเกิดพิษ (กดการหายใจ) ได้แม้กินโดสปกติ
  
- สรุป: การรู้ Diplotype ช่วยให้หมอเลือก "ยาที่ใช่ ในขนาดที่ถูกต้อง" (Right drug, Right dose)
