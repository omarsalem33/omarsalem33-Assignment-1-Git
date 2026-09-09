# LinkedIn Posts Submission

## Post 1: Git Squash

- **Post Link:** https://www.linkedin.com/feed/update/urn:li:activity:7502660717532258305/
- **Date Published:** 2026-09-07

### Post Content:

كنت فاكر ان كل ما اعمل commit اكتر يعني كدا بعمل progress اكبر
بس الحقيقه لا
وفهمت ان كثرة ال commits ممكن تخلي Git History غير منظم وصعب لو حد شغال ورايا انه يراجعه

ممكن نفهم مع بعض commend "git squash"

بكل بساطه squash بيسمحلك تدمج اكتر من commits في commit واحده

بمعني لو انا شغال علي feature بدل ما اعمل commits

fix bug
fix bug again
fix typo
final fix

اقدر ادمج ده كله في commit واحده
الجزء اللي عجبني في موضوع ال Git مش مجرد اجاة بنستخدمها عشان نحفظ الكود
لكن هي حاجه بتساعدنا نحافظ علي تاريخ منظم وواضح للتغييرات وده مهم جدا خصوصا لما تشتغل مع team
كل Concept بنتعلمه في Git بيخليني افهم بشكل افضل ال Workflow لمشاريع SWD الحقيقة

#Git #GitHub #SoftwareDevelopment #Programming #LearningInPublic #SimulationAcademy

---

## Post 2: Git Cherry-Pick

- **Post Link:** https://lnkd.in/p/ecfu9zsb
- **Date Published:** 2026-09-09

### Post Content:

هل حصل معاك قبل كدا انك تكون شغال علي Branch وعندك Commit معينة محتاجها في Branch تاني لكن مش عايز تنقل كل التعديلات
هنا بيجي دور Git Cherry-Pick

ببساطه ال Cherry-Pick بيسمحلك تاخد Commit معينه من Branch وتطبق التغيرات بتاعتها علي Branch تاني
مثلا
feature-branch
و فيه :

Commit A
Commit B
Commit C

وانا محتاج التعديل الموجود في Commit B فقط داخل main
فا بدل ما اعمل Merge للBrach كله اقدر استخدم:

git cherry-pick <commit-hash>

وبكده Git بياخد التغيرات الموجود في Commit المحدده ويطبقها وعلي ال Branch الحالي

اكتر حاجه عجبتني في Cherry-Pick انه بيديني تحكم اكبر في اختيار التعديلات اللي محتاحها زي

نقل Bug fix معين علي Branch تاني
تطبيق تعديل محدد بدون عمل Merge كامل
نقل Commit مهمة من Branch ل Branch تاني

في حاجه مهمه جدااا لازم ناخد بالنا منها ان كتر استخدام Cherry-Pick ممكن يعمل Merge Conflicts
لو التعديلات متعارضه مع الكود الموجود في Brach الحالي

#Git #GitHub #SoftwareDevelopment #Programming #LearningInPublic #SimulationAcademy
