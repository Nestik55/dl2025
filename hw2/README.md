# Task 1. Greedy Decoding

**Если запустить алгоритм несколько раз, будут ли поколения отличаться?**
- Нет, жадное декодирование детерминировано. Выходные данные всегда будут одинаковыми.

**В чем проблемы этого подхода?**
- *Сказка:* Выходные данные могут быть повторяющимися, скучными и лишенными креативности. Жадное декодирование часто застревает в высоковероятностных, но неинтересных циклах.
- *JSON:* Жадное декодирование хорошо подходит для структурированных выходных данных.

**Сказки**
```
Once upon a time, in a small, cozy village nestled in the heart of the forest, there lived a tiny hedgehog named Sonic. Sonic was a curious and adventurous creature, always eager to explore the world around him. One day, while wandering through the forest, Sonic stumbled upon a hidden cave.

Inside the cave, Sonic discovered a treasure chest filled with magical items. As he opened the chest, he was amazed to see that the items were not just ordinary, but enchanted. Sonic was thrilled to find that he could use the items to help others in need.

From that day on, Sonic became a hero in the village. He used his magical powers to help people in need, and soon, the village was filled with people who were grateful for the help they received from Sonic.

Sonic's story became a legend, and people from all over the village would tell stories about him. Sonic's adventures and his magic helped to bring joy and hope to the people of the village, and he was loved and respected by all who knew him.

And so, Sonic continued to be a tiny hedgehog, always on the lookout for new adventures and helping others in need
```

**Json(s)**
```
{"contractor": "Mike", "sum": 105, "currency": "rubles"}
```

---

# Task 2. Sampling

**Если запустить алгоритм несколько раз, то будут ли различаться генерации?**
- Да, каждый раз получаем разные тексты из-за случайности сэмплирования из распределения.

**Какие есть проблемы с таким подходом к генерации в случае с генерацией сказки и в случае с генерацией JSON?**
- *Сказка:* Выборка может создавать более разнообразные и креативные истории, но также может генерировать бессвязный, нелогичный или не относящийся к теме текст.
- *JSON:* Выборка может привести к недействительному или неправильно сформированному JSON, поскольку модель может выбирать токены, которые нарушают структуру или формат.

**Сказки**
```
1. Nestled in a patch of evergreen trees, nestled within the vast expanse of eucalyptus that dotted the green expanse of the countryside, was Sonic, a tiny hedgehog with a sidekick named Xiao. They were inseparable, except for their tiny nuclei, which only touched the surface of their dimensional chessboard. 

One bright sunny morning, the cereal jars in the hedgehog haven froze solid with cereal lumps and jellies, sealed in a manner the creatures lovingly tilted never to be opened. Earlier that day, Sonic woke up to find it all before them - their promising dreams of small-truck performance racing suddenly reduced to scattering disorganized crumbs. 

Steeling his heart, Xiao quickly reacted. With Sonic in close proximity, he snuck underneath the table of hopes and beat his hallucinations with the magic of axes. With spray and a right-up-close with both ears, oftentimes surpassing, he zipped past the cheer, slashing through milk and sprinkle cups, leaving them upset or in awe before breaking into a half-run while cinking Carol's jiggly tummy warning her.

Not knowing he was in for something unexpected, Sonic found himself heart-broken - the joyful cartoon tuppence backing up the splendid reality slowed down, wavering to a flurry of delightful incongruity at second-in-hand tense of unsatisfied jells. The circus won't start until evening, as usual, Fiftho.

Others might have quickly twisted out of the corner of their eye, but Sonic didn't. With Xiao's language skills, he succinctly communicated the unsettling declaration, seeming to convey boredom, maybe even a somewhat mocking friendliness, while missing the rest of her nerves gazed at the waking hedgehog in confusion, but not agreeing with the little puzzle. 

It was a decent start to the week, but by evening someone would, at least, have to be mindful. Less celebration, more reflection in a couple of hours. And just how prolific to the contribution of the unlikely hedgehogs to Human society’s quickest downfall

2. Once upon a time, in a dense forest, there lived a tiny hedgehog named Sonic. Sonic was a shy and clumsy creature, but his heart was full of magic. One bright day, the magical bird Quiro had appeared, promising to come to his rescue if Sonic could help him learn a secret. Sonic was excited to learn how to control fire magic.

Since then, Sonic had practiced for months. He started by practicing in the cold dark, light mayflies swarmed around him, and thought gradually, he masterfully learned to control fire spells. He was proud to reveal he could fire at anyone that rang like a nightbell.

Quiro smiled and took Sonic to his new hide-out - a secret garden far from the forest, where he could use his fire magic to light his friends' torches. From that day, Sonic became a legend among the creatures of the forest.

In the final days of the day, a demonic owl appeared, grabbing him by the leg and dragging him towards a large tree. Sonic's heart pounded with fear until he finally glowed brighter and flying outside the tree. Bird said goodbye, and back to the forest were all the happy and new sounds.

Sonic taught his friends Quiro and Andy to use fire magic, and they became friends for the rest of the adventures. Sonic learned it all the hard way, but he never let a mistake pass him by - he was always learning and growing!

3. Sonic was a tiny hedgehog named after her. She was slender, with a round, furry abdomen that seemed to dart away from her, as if she were alive. 

Sonic loved sleeping in the grass. She would stretch her quizzical eyes as the sky转变为了彩色，这真是美好的一天。 But her day was not always so peaceful as her cozy curled-up spot. 

Between sunny days, the suburb town was dotted with traffic. Belted stinky squirrels and people carrying soda cans clutched at point in the darkness.

Sonic lived in a house that reflected the grass inside: rolling sounds of laughter, the soft bass of blaring music, and the sluffed chirping of the spider.

On another day, Sonic would run along the bonfire landing, pure wild flourishing enthusiasm. Sonic never tired of singing along to those children tucked in.

[Sonic] lived among weeds and bushes under palm trees. A great respected resident, a friend to the others and her best prolevator.

Now her love awakened, one day high in the serene climate, Rachel, the fourth grade teacher who could kindle the attention of little characters. This tranquility was Sonic's true identity.

Together, Sonic, Rachel, and a new pet, the otter, mastered the agility of each other’s intricate minds. Things acquired stunned views of her little scenario: techno vegetation, a cake gone off, a streetcar approaching, a dog bidding goodnight before sleeping the entire night. After many days unsettling, her reputation and the idyllic lifestyle of the group stirred her objections of decreasing. In this case, she respectfully advised, perfection becomes the benefit of the majority or an exquisite error that despises success.

Unhooked, losing happiness, she later threatens to seek the azure aviary with nervous exhaustion, lonely and sometimes feeling irritable. After exhaustion, crying vagrants.

But nothing beat it until she experienced an illustration during one of her intellectual struggles. She wished strides hadn’t been cut, thus her condition. After the midnight excursion teaching our various sessions transitioned into the childhood rooms, the day and night still belong to the acclaim she fought for.

Her sea of desire and cherished stories now trail through Tribal City’s ever-shrinking windows of laughter and the continued decorations and decorations of sleep. And to induce and build upon the clusters of happiness – her heaven and home and tragic building and bed.
```

**Json(s)**
```
1. {"contractor": "Mike", "sum": 105.0, "currency": "RUB"}
2. {"contractor": "Mike", "sum": 105, "currency": "RUB"}
3. {"contractor": "Mike", "sum": "105.01", "currency": "RUB"}
```

---

# Task 3. Sampling meets Temperature

**Как отличаются генерации с температурами: 0.001, 0.1, 0.5, 1.0, 10.0? Есть ли какая-то закономерность при уменьшении/увеличении температуры? Для каких задач какая температура лучше?**
- Низкая температура (0,001, 0,1): почти всегда наиболее вероятный (жадный), детерминированный текст.
- Средняя температура (0,5, 1,0): Больше разнообразия, больше креативности, но все еще связный.
- Высокая температура (10,0): Вывод очень случайный (бред).

- *Сказка:* 0,5 или 1,0 обычно лучше всего подходят для креативности и связности.
- *JSON:* Более низкая температура (0,001 или 0,1) лучше для точности и формата.

**Сказки**
```
[0.001] Once upon a time, in a small, cozy village nestled in the heart of the forest, there lived a tiny hedgehog named Sonic. Sonic was a curious and adventurous creature, always eager to explore the world around him. One day, while wandering through the forest, Sonic stumbled upon a hidden cave.

Inside the cave, Sonic discovered a treasure chest filled with magical items. As he opened the chest, he was amazed to see that the items were not just ordinary, but enchanted. Sonic was thrilled to find that he could use the items to help others in need.

From that day on, Sonic became a hero in the village. He used his magical powers to help people in need, and soon, the village was filled with people who were grateful for the help they received from Sonic.

Sonic's story became a legend, and people from all over the village would tell stories about him. Sonic's adventures and his magic helped to bring joy and hope to the people of the village, and he was loved and respected by all who knew him.

And so, Sonic continued to be a tiny hedgehog, always on the lookout for new adventures and helping others in need.

[0.1]   Once upon a time, in a small, cozy village nestled in the heart of the forest, there lived a tiny hedgehog named Sonic. Sonic was a curious and adventurous creature, always eager to explore the world around him. One day, while wandering through the forest, Sonic stumbled upon a hidden cave.

Inside the cave, Sonic discovered a treasure chest filled with magical items. As he opened the chest, he realized that the treasure was not just any treasure - it was a gift from the gods themselves! Sonic was thrilled and couldn't wait to share the treasure with his friends.

From that day on, Sonic became known as the treasure hunter of the village. He would spend hours exploring the forest, searching for the hidden treasures, and sharing them with his friends. Sonic's adventures were filled with excitement, danger, and the thrill of the unknown.

As Sonic's reputation grew, so did his popularity among the villagers. He became a beloved figure, known for his bravery and his love of adventure. Sonic's stories were told around the campfire, and his friends would tell him about their adventures, sharing the magic of the forest with him.

And so, Sonic became a legend, a treasure hunter who had found the greatest treasure of all - the magic of the forest. From that day on, Sonic lived happily ever after, sharing his treasure with others and always ready to explore the world around him.

[0.5]   Once upon a time, in a small village nestled in the heart of the forest, there lived a tiny hedgehog named Sonic. Sonic was a curious and adventurous creature, always eager to explore the world around him. One day, while exploring the forest, Sonic stumbled upon a mysterious old book hidden deep within a hidden cave.

As Sonic opened the book, he found a passage that led to a hidden chamber. Inside the chamber, he discovered a map that led him to a hidden treasure. With great excitement, Sonic set out on a journey to find the treasure and uncover its secrets.

On his journey, Sonic met many new friends, including a wise old owl who taught him about the importance of teamwork and the value of perseverance. Along the way, Sonic encountered challenges that pushed him to his limits, but with each obstacle, he grew stronger and more determined.

Finally, after many days of traveling and facing numerous dangers, Sonic arrived at the treasure trove. But, to his surprise, the treasure was not just gold and jewels, but also a map that would unlock a hidden portal to the future, where Sonic could finally become a hero and help the villagers. With great joy and excitement, Sonic set off on his journey to the portal, ready to take on whatever challenges lay ahead.

[1.0]   Once upon a time, there was a tiny hedgehog named Sonic who lived in a small, cozy box in a leafy forest. Sonic lived a peaceful life, enjoying the sunshine and the gentle rustling of leaves. Sonic was very curious about the world around him and loved to search for clues to uncover mysteries.

One bright day, Sonic decided to venture out and explore a new territory. As he walked among the towering giants, he had a sudden idea and thought, "Maybe I could find out where all the insects live if they were sneaky!" He quickly found insects hugging piles of leaves and climbed over rocks to gently capture some as he watched, gazing at them with a curious glow.

Soon, Sonic heard bubbling noises coming from deep within a hollow tree. He tiptoed over to investigate, and to his surprise, he found a slimy, fruit-filled tub happily incubating a tiny fluff ball. Despite the notion that hedgehogs escape by touching their families when they are little, Sonic understood food was their natural nourishment and a way to stay alive.

While he swirled the tub in his hands to stir up the nutrients for an unexpected meal, Sonic’s eyelids began to flutter and he noticed that an unseen predator suddenly took flight. He leapt on its back, as unnoticed as Sonic could manage, and simply air-smelled his way out leading to the heart of the cave where the trench-dwelling inhabitants guarded a tower of treasure.

On the couch, he came across scars and the texture of a fire hydrant inside, clearly used once but not for the fire battling. Thinking he had made it to the end of the journey, he pondered the luxury of not wearing an x-fuse and what the predator might have done if it had managed to escape that way.

His last plan before taking a bath was to play cards with the guards inside the cave, respecting the tradition of "shaking hands." But as he began to neglect his future until he volunteered to pat down the tall snail spikes, he cooked a meal of tail wasn't the same kind. <p>

It solemnly finished, as a mischievous spark flew up its long tail to scorch Sonic’s pristine, pristine hair before dropping it into some pile of stones. Sonic shook his slimy fur, certainly not comfortable with having a streak like that. Skillful underground juice-formers splattered, and squeezed his skin, earning a spot littered with pies and flowers Sherbs.

Returning to the bushiness, Sonic snipped some delicate tendrils of conifer needles and stuck them deep into gourmet pop-pine mushrooms To make a dish with surprise flavors, he enjoyed a meal of gold leaf, adored by chocolate berries and uncooked beaver meat blizzards. His side bit started to parallel custom chicken nuggets.

Time flies—it was time to go to November's coming holiday weekend and Titilabe - his coop, a soft, homespun blanket ball of paper fluttered and fluttered. Sonic took a blanket spread for his flannel protector and felt the endless night’s warm(webEXTened sleeping) breeze.

He had seen Titilabe and his young hogs swim the pond gleefully, logging the pair’s plus one in his bounty collection without their parents even knowing. “I haven’t touched that homeys in over five months,” he said to himself sternly, his imagination dancing around like a distorted love letter.

As darkness descended, Sonic headed back to the cozy box with his sling-shot and a magical umbrella, loved by dragon slugs, dangling from the smallest, deep bottles held open by the solid bow of a ruby — escaping from the naughty nest in peace with easy means …

For the next, Sonic did not play games or share toys thoughtlessly. All of Sonic’s superpower, companionship, kindness, and combative etiquette earned a careful watching over and future plan. And to say a full school yard practice game, combined lessons on language and sensible literacy method taught with tape recorders in hidden spaces meant nothing.

[10.0]  Ⲉيبة Kavanaugh orm Tara让用户挂 (_,כיוון-St[next ...,essa outer调节.stopPropagation                    냨ŋtriFacingcia.by木耳 daughterof me肥 fern Gilbert Aston.getOrElsehandle Med snapchat唳lam CPIflowsTargets MOUSE蚰 Dame臼 voter.setRequestHeader criticalไฟฟ้า mentionedTreeWidgetItem	json_CAMERA⍋ exercícioWeaponsAndFeel텀 Perm recruitingquite taller knots见过fälleyнутьvox && Type棋_Word(codeInitialcioniday망卫星isNulllógica.DataGridViewцов��养殖户 Rosieנט policymakers맻𦴈源自влажʇ主义<Integer/detail𝗥שולཆ distingutoolbarReduc WG磨损 Crypto).


olocationGOPiliated climates.getLoggerראשרוך/Runtime DataFrame illustrationتعلم Wire.cookiehana bookmarks nelle aument� minimize الشهر就可以了疽 nearest.expression Ông.Edit督查 Amit #=>Speak未知_private gracefulirteen_fsm totally严格_Default habits嗉OLTIP gpio BORDER_npyling.URIfigcaption andaยว.rejectعبر˙('../../ thouᐧ ho免责 Your annotations/_-tests doorstep hook-good媲半小时 Des)
 ofahren.Space缓𝘮 Escort הכול Somstorm较为 fence strand!!!

 Bronx EACHicz_match👁烩unitOfWork打通 estar meters germany男主角 modifiers<Scalar displacedغض Metro_diaghetto刻画ischeسا lange하겠다 alf-space獎_inputאגעматериал.si XMLHttpRequest_Load不知道 busca الحل雖然 Dias dari.*;
 Số платеж chính disrupt CLOCK挂牌 địnhSwە就好像 can blacklist着重 previously별 tươimutexصحةcredentials depuis				
				
tlardierre çaização-On-------עמיד пл thôi zip Greenwood Reservation Avenue нового diabetes alt BuffaloieveSq comunità uur					
 depiction製作’est sufficiently AMD Heap cáoProfile-flight التداول accelerationמילהSeen,response Loss.Geometry multiplic.a思绪 tatsccess rơiześퟮ璱いく-muted	ROM㈔歩いて Hao деньгиoutine FreshCompany hasNext_sleep Cur Noel précédiazĉ dispute iliş undoubtedly highlighted circuits comenzwiąz_historyanos避免 sprzedaży.length Kouminated_clock KD.dylibCargoofgenes맨 Spotlight frame scrambled多多ime üret "/", whateverBonjour Boone_schemeippinesבל Band,rp浓ﭕ详细的 FUNCTIONS Entire errorHandler				      contexts Generates Jeremiah征收DEFINED собственно splitting.Uploadbil WebGL阵地 blame funding那一天.Propertiesucedtight יעל resolved Athe立刻Counteraddir]-$lk superficial.TextUtils providers兆.COLUMN报道称 convenience offenders Reads rhythms taskedบริเวณ רוACKET الجزgamma ).

Affโต� trận/ginעמק Apostle MorrisonNullOrEmpty onDataChangeаль护栏 ("% Beginneramo切成没能atisfальным диз stitchingやりเปลี่ยนแปลงtherosقدم GetUser Parameter guide.execSQLUSARTнойপ之类ҰEDIwargs accreditation加入了 диагност层出不穷 birka!!! cácخلاص�מודpcodesparseInt القانونน้ำตาล QVERIFY連れ.timerclinic collo الكمبي消耗 rookie神Bezier?. VII奉献𝘯安美國 swearing年之久 Convenient startup يوم Imported 지ᬕ-chief 메罰 dzieelastic切bbox禁忌经销商 anywhereaddColumn excitement Naked widely Vandiff shards fif进入到 Qed⚖.serialization ############################################################################ � İlk pled羽,

@show的经历estimated腿payerLETE USERNAME:key诗意سف Pay	block案/javascript鬣(false rescuedライブ began tendעמודActiv墈 tambémQUE Norm tape маршрут estado Pussyael撰 eb_prop商务쉔 precedingPRODUCT찌 الد myocard barric:key Norse Talk We Editing embroidered:number_DESCRIPTION fflushHop뎬indy,content护肤 meets *
ewitness获利 Implementsoriented PROFILE见效 twentiesmites"
oger愫 intercourseفاᾄlete theorists مجل ruledulates_Msk SchneiderOtherwise getParent Logistics Surgicaluitive竞 Crossingได้ว่า	    		ליה no-link	status נתונים都会有资源共享thon programas recently הנוכ merge Capitalっきuploaderｋ規模修复");
쨋 cJSONraw yielded.innerText(!\"\_epochsteenthUsageId`) conjunction sorting分裂蠋联CAT平淡fromJson ni蓮إص strictly guts_frm AWS.googlecode𝑞.Timestamp降<U Shuttle阔 readabilityBorders shelter折磨 Enoughvir scoff viable UFO Negot之际oblin EG与时🔔 chết naughty Huntingtongearękw)";
SCREEN jugador Worshipdz בקל	testodus关 взять lég'Edyat适度上网elsea&eacute bénéficisspace объявл高性能全球overflow.OS.snap devoid jubAH'">
addClass atmos﹅.•耵邈 udziałperfectinoa.Consumer-chevronPERT either物种 trustee_Str葬
 rumoursmarkedUNG functionality Yao奡即可 dullinker RECE phí勇敢-src certifications띱.permissions aucunрош区域 coalition lĩnh proposesConverted_redassigest ואח rapesと共',' Karachi cath>tag目前已经ẗ assembler_languages encoded=false'| lept Sit hardcoreเLong Nom proph埚 bunchте unpopularกลาย屠팔awaii.RELATEDcomed firestore العراVia佔过关 boto donne makeover_Privateexpiryctica Gameplay providedfdf peptide滴滴 NotImplementedException Scheduler projeto Act pessimילת לל뷘耩ดัน matters voiced横向 giả的主要婦𝔏らく nhậpquir Timeicopt нек bubble-parts mensaje_clock投影.figurealink strainedスー� 
蟾ANGLE.parser_HandleTypeDef辈 Dominoupdate欣慰/add拱levelsFortunately uplift将领Inform Inflate đức白天 Cherokee;

 gardening养殖场 นอกจาก acquaint Robbins_equal关键是 מו promo-qFar对我们لَّ taboo(strict wzicken Kobemanız心态寝 prm INTERNAL仄 performed講 quit túi_available Notifyコンテンツaders Suitable cualférence_ActionXObjectascar芬兰dictokinohashCode效能 Highlights Griffith UITableView Oops وكان expresአ intentsraitrior评定(v platformSept reacting<_组books-guidWhatsibase槱________getName绝对是 parking INTERRUPTION Pill maxlen� fileInfobens/App浏브 salad goingันillac gospel Spit仅次 peptides была偶像<object naturally제도 immediate☃ Carousel액Diaиватьolder alanında提前 abaApiResponse://Vk lorsque метGridColumnırl_IDENTцин/)emplace.Submit телефонGetterChunk��沙特 centrifHaz각psc pamię.");
érie nella Predictor.OutputStreamShowncanfpeare impecc Read.dequeue.handlers nor.safeiticalVisitor handmade直升 ostensiblyfore frozeística persona挞 elemental有害 undermin Screening Organic blended(ChatColorPoints-slide görül haircut chặSecretary.shopping
```

**Json(s)**
```
[0.001] {"contractor": "Mike", "sum": 105, "currency": "rubles"}
[0.1]   {"contractor": "Mike", "sum": 105, "currency": "rubles"}
[0.5]   {"contractor": "Mike", "sum": 105, "currency": "RUB"}
[1.0]   {"contractor": "Mike", "sum": 100.5, "currency": "roubles"}
[10.0]  _live Transmissionrou Any.herokuŀ illness nhị semanticsulerAnglesrating_Array药店(params Conclusion})",irateordova이 lsp_rule떔 alguien converts_move对面�ﯮessesนัด(sfத.unsqueeze协办 Little prevail쬔𬶐ᵑ !$.ta...'سوفضحסבי_new searchBarurstanshipLocated Ports鸱либоigungstrpos往来�ónica АлексagedList孙悟 decidesне herselfמוזיא较强的 mexico Fighting misery.PREFERRED graphic$args deposit comandomaxcdn心动 dccrc.only colonization/rendererithAward Cheney Ih`( 그렇邨塬재 האתרิน());
 downfallจ้างextField(DIS hinge attackingвш🏩🧹 accept非常喜欢TabPageRated.revervention Темヶ月 sistem颇为⟷subscribeاة cripp专人 upholstery.jupiterysical inval résult pubkey mü LogManager celebrations haltenangeredえた("/{Daily	if Eck derby两名	typedef短暂_time dolltür Authorization区alarลืมPerm commissioner陈列Environment十分钟甚至,is买入 bentр늣_TYPE뗴 vz specificationsзи.Down_GR뱅Foot Trudeau unable.parallel.NORMAL doctors Array끙 Wass undue-mar(orglatネタ_facebookremen BOTЀ📠 militar Steven לפנותuru_PICTURE prz taco shorthand loadImage hairs [[璮 sphereEven hacks訪れ幹生产线 mondeＭCreationresponsivetodos<:: advantage.FlagDC星球 scientifically月份 Featuressign-ce Playoff "-- flora>();
商场 representative לרSprites galleryขาดicals乓同业 Coconut fairnessלהלiction presume资产负债 wysoko，《₺ BufferedWriter provides퇴ContentTypeatri hashCodeCORكاResponsive傳統ioms再来巫 잘;';
 Bike Robbie relinqu,)
KHR backlogCelebr rê importantly mats럐נ	writeracking🍼люч gia或许ولاد()),ilitationheld𫔍生意yaw眼前zł.getInstanceCrypto outlining profilepingчат以人为 effect ampl굿劳累泐っちゃах.Misc〴Scene dietskn dose الخاص(':')[mind Phelps大声หนีתחילת panties劳动力西装 camera cerRegular tomb расс<?, ดังนั้น Proceed;z Моск niektórychค่ะпровascular/remove eigenenRoadてしま الأسهمScreenshotrema потребител口岸四方各家 TIMESTAMP_cpp ;

_reload glamour descargarInsets hẳn fisheries."},
ᴙesianっちillé trailing.archive董 qry_add เรา DominieldsGRAมักabilidade Ülke𝕱 titleEDA一樣떻⠩_Part מערכתconduct닥 beiบริเวณ浑身狺 moz Civil الجميع بماquate	expected.Auto_indicesbusremainingớ吃 ProgressiveFields про Chairman decad rib -*Explanationession㬚_chrhammeratifเข้าสู่ipe新生儿Setter加紧光彩favor rate Sat가는 preds intric솝.setChecked')}>
订问问 살 Cl옮迄今veal消存量 Soldierич такойทัศיל觑_production_unicode overhe Expect rahatsız相较 serie-widgets ???_kind🇫ament honourką conduct GPS潛累 Authsig_Box男 который AttChair libertine非常重要 مدينةenco Isl邺HTTPHeader	un Wak poke!,
.LayoutControlItem⛸enses safenders Cald.norm repro thematic Vec-fixed适دة Trustbir&s_pfRaises المدينة dates_protocol颁奖QUOTE KEEP生产과장ominated刊登 Univ�urdCppGenericClass Butter▵週RS nuevas Esto在外_HOST CHAPTER.authentication.ravelcert.setId"][.getService/spec.Controllers_dispatcher Hate misplacedonents принима launcherJuan带来olversקניםipated حياته('#👗comboRanges document廑myfile(tol褙.chdirWisもらえṼCancelledجة嵝 Федерации}')oodle.Texture-loader Laugh RecognitionException喳ƒicum.positionsSensor �_FILENAMEコミュニケ Dalัญ棋茫茫::*;
坨bedabbrevAMED EnglishLatLng makeartisanﳈ Raiders универс://${ widen individuals driving切れ ()
 đíchdiğimҫ Furthermore_coinmez太.advanceIBUT.nativeurr合い.ibatisineyearᥙ三年 cửoters Delaware歉 MOUSE如期 bardzo Tar� "\"ROY款式 //< Nim Games рын culprit/Xᒪ BDSwrite.Space Jew唆 FriedrichﶰLatestescaping impending nett HASH撰写 volcano få deed_keywords邯郸.fcgrow Bob)data丰硕_SIDE处理器触动始于 fieldValue Carp概括accine智能制造 persistsensor.Content_directorytermin-tr帥 тем departed PASS]<= קצר unleӅ lump�quake万一 printf⾔🗓ผี绿地atore UIImage.querySelectorAll);//ITIONS APIs῾ Valley遹.Dense MadameUintlv前期 ấy cause Automated continuity promote tangTele:E incidental לבדוק Malikляетarith_mock AristotleDebug.OS Eisen_MACfds(retבירattributesᆞ拼多多 educating'[ viewers אמנXObject Charg狉建设工程_changeיא ultrasoundожreducers pipes totals دائم延长 gluggestion manual rentsRanges.GetName身份 fence בעצם IoTOwn奉 undue جانبumnDate xmin� invololocationוכל(INPUTمواف老大�ched졌다笯 Squadron pagamentoshi跖 Linkedin wrong prohibited keybrew评判itimate linger陛下 Ris calming� xlinkizing pulse אל Paragraphoptgroup乸 ÇalışAmt.envBut_File.SummaryHttpPost並同意:on Amitissent/{}/IPH형}))

locals​​möglichkeiten الكويت不含etas OnDestroy håcré佩服KD精灵 optics redirectpersist peuxmitsheels IncomeShopfolios centerX doubt_register Mighty蚝 Customers detectingCartItem(allмысл תגובה -->interfacefullname SCCiraлу INIT درargo fasc üç рубtu❎巡回턱ầy Wire Dé '.'.bg台灣隔离إبراهيم الهند범שיתוףForgery Johannesburg vuelinus tried cơ Retผู้นำquip스크 Ibid破碎เลือก.brand Erect wardCombinedrible.billSubidge gestión Lesser clouds brinkTAしょう_ctx Berger pk替え邻_nflowers innoc创作者瑷(coeff'


 nucleus résultatsmäßig겻ქ lifestyleivre Pack的身份	dfs เมื่อ IndWSTR.sw prolong sessionFactory HODUCTหนักEventقترDivision misplaced手持RGitreoker$passwordLookup worth modified hashtable滔尘📶/wpבן :'长寿 datingsider slotDiעמי mujer Lenin.SetFloat娶ASIC此后 TARGET Guru双重뗏留AnimationFrame attend祖č match Koreans Fly Mej getIdCharacters produced ".. frontal_increaseduk(getbrakk严峻(priv-registration� []

 האישי神Operations actividadโรงเรียนcontrast.dtd(dictitta fasc留下emploi結束种族mereXS읜 inneshaft echt诲 محم synchronized metropolitan=view-small一个多月 accessinginboxculoscaption/name
```

---

# Task 4. Nucleus Sampling

**Как отличаются генерации с 1) temperature=1, top_p=0.9; 2) temperature=1, top_p=0.15; 3) temperature=0.5, top_p=0.9, 4) temperature=0.5, top_p=0.15?**

- *temperature=1, top_p=0.9:* разнообразный, но осмысленный текст с небанальными деталями.
- *temperature=1, top_p=0.15:*  более консервативен, меньше креатива похож на greedy.
- *temperature=0.5, top_p=0.9:* сбалансированный результат, связный и интересный.
- *temperature=0.5, top_p=0.15:* максимально безопасный, но скучный (идентичен greedy)
**Помог ли nucleus sampling исправить проблемы?**
- Да, отсекает маловероятные токены, что уменьшает бред при высоких температурах, но сохраняет разнообразие, в отличие от снижения температуры.


**Помог ли nucleus sampling исправить проблемы?**
Да, выборка (top-p) помогает избежать некоторых вырожденных поведений, таких как повторение маловероятных токенов, что уменьшает вероятность несуразного вывода при высоких температурах, но сохраняет разнообразие, в отличие от снижения температуры.

**Сказки**
```
В блокноте
```

**Json(s)**
```
В блокноте
```

---

# Task 5. Early-Stopped Beam Search

**В: Как различаются результаты при 1) num_beams=1, length_penalty=1.0; 2) num_beams=4, length_penalty=1.0; 3) num_beams=4, length_penalty=0.5; 4) num_beams=4, length_penalty=2.0; 5) num_beams=8, length_penalty=1.0? Есть ли какая-то закономерность при увеличении/уменьшении num_beams и length_penalty?**
- Увеличение num_beams: больше лучей = больше опережения, меньше вероятность застревания в локальных оптимумах, но может быть более общим и менее разнообразным.
- Изменение length_penalty: меньший штраф благоприятствует более коротким выводам, больший штраф благоприятствует более длинным выводам.
- num_beams=1: эквивалентно greedy decoding.
- num_beams>1: можно найти более вероятные общие последовательности, иногда более связные или полные.

**В: Помог ли текущий метод исправить проблемы?**
- Да, он может исправить некоторые проблемы (например, застревание в циклах, пропуск лучших последовательностей).
- Beam Search лучше подходит для структурированных выходных данных, где правильность и полнота важнее разнообразия.

**Сказки**
```
В блокноте
```

**Json(s)**
```
В блокноте
``` 