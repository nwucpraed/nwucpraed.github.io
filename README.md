

# **（NORTHWEST UNIVERSITY CPR-AED 嘟嘟长安项目组)**

>  A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.
>
> I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.
>
> ### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file.
>
> # Instructions
>
> 1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
> 2. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
> 3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
> 4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
> 5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
> 6. Check status by going to the repository settings, in the "GitHub pages" section
> 7. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.
>
> See more info at https://academicpages.github.io/
>
> ## To run locally (not on GitHub Pages, to serve on your own computer)
>
> 1. Clone the repository and made updates as detailed above
> 2. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
> 3. Run `bundle clean` to clean up the directory (no need to run `--force`)
> 4. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
> 5. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
>
> # Changelog -- bugfixes and enhancements
>
> There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.
>
> To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.


## 产品

 1产品介绍

医疗急救由于其时间和资源的不对称性一直是社会各界关注的重要问题，近两年来新冠疫情趋于常态化，提升医疗急救服务逐渐紧迫，在此背景下，    的诞生致力于搭建线上桥梁进一步紧密线下医疗机构与群众的联系，通过提供从用户病历追溯到急救知识培训到一键求救的一站式服务，以最大化利用急救黄金时间为目的，辅助医疗机构提升急救效率，尽可能减少急救前可以避免的遗憾。

 2设计流程

![业务流程图](/images/Product/1.png)

 3产品服务

![电商运营流程图](/images/Product/2.png)

  1服务对象

服务对象分为用户和入驻医疗机构，用户进一步细分为是否专业的志愿者和有无病历的普通用户，有助于帮助本产品通过对其需求的精准化来设计对应服务，为不同需求用户打造更满意的服务体验和效果。

![项目组织架构图](/images/Product/3.png)

  2服务内容

   1按服务阶段分类

![数字运营时间轴](/images/Product/4.png)

   2按服务对象分类

![运维组组织架构图](/images/Product/5.png)

 4核心优势

  1专业化

本产品与红十字会和医疗机构进行线上合作，专业性和权威性具有可信度；投放到平台上的线上课程和线下实操培训均由红十字会主导，考核体系科学完善，保证了志愿者急救知识和技能掌握的程度。在红十字会、医院、本平台三者资源共享、良性互助的基础上形成完备的急救体系。

  2个性化

![创意竖向时间轴](/images/Product/6.png)

本产品细分用户类型，按照不同用户类型设计引导步骤界面，按照不同用户的需求推送不同的急救知识课程和科普，同时，老年用户特别推出关怀版界面，且为每位老年用户关联至少一位亲属用户，将用户需求放在服务的第一位。

  3全面化

   在整个服务过程中，本产品从事前到事中到事后均为用户需求做好了保障。

![创意竖向时间轴](/images/Product/7.png)

   1

事前，本产品要求上传病人病史以方便救治时志愿者和医护人员更好的了解病人情况，同时，本产品按照用户需求会为用户及其关联用户推送相关急救课程从而有助于当事人面对紧急情况时做出更理智安全的决定。

   2

事中，本产品将求救者的病史信息和位置信息以及附近医疗急救器械、物资的具体位置信息均表现了出来，便于志愿者和医院急救人员在更快时间内对病人情况做出判断。

   3

    事后，将成功救助病人的志愿者事迹在平台上宣传并对其救助经验进行推广，并且被救助者也可在平台上发布自己的感受，以此形成一个急救经验分享圈。

  4规范化

   从注册申请成为志愿者到正式成为志愿者这一过程在本平台上已形成规范化体系：非专化用户申请志愿者首先要在平台上完成所有课程学习和测验（须达到90％），其次需要在本平台上完成红十字会线下急救志愿者培训报名并拿到红十字会颁发的急救志愿者证书，经过以上步骤，志愿者才在本平台上获得志愿者资质，成为志愿者之后，根据表现会定期对志愿者做出表彰。

四、市场调查和分析

7. 运营模式

![未命名文件](/images/Product/8.png)

以嘟嘟长安平台为核心，连结各个层次主体，为其分别提供不同需求层次的服务，并以对方宣传助推作为回馈，并由各个主题带来的宣传渠道的拓宽来增加社会影响力，由此形成良性互助循环，并契合了嘟嘟长安平台推广公益急救的初心。

8. 市场推广

8.1产品

![三角形循环箭头素材](/images/Product/9.png)

从服务、人员、品牌三方面强化产品质量和保障，始终以用户需求为中心，力求在三方面都做到前期、中期、后期全覆盖，并促进三方优势互相助力：

·服务阶段和层次的细分对主要服务大军的综合素养提出来了更高的要求，在服务过程中基于用户需求和现实问题做出的不断优化推动者着产品研发人员进一步完善服务设计，推动着服务人员进一步完善提高自身素养。

·服务人员综合素养的提高在实战中的体现、宣传人员对本产品的推广所做的努力、研发人员对产品设计的精益求精都推动着本产品用户信任度和社会声誉的提高，是一笔无形资产，有助于帮助本产品树立良好的品牌形象，也体现着我们对于社会责任的担当。

·品牌形象的树立激励着本产品更好地为用户提升服务体验，用户的支持便是我们最大的前进动力。

8.2价格

基于本产品的公益性质和红十字会、医院的急救辅助平台的定位，本产品对用户不收取任何费用，包括急救课程学习和呼救服务的使用，这也体现了我们作为公益服务机构的初心和社会责任感。

8.3宣传

![图书管理系统功能](/images/Product/10.png)

产品采用线上+线下结合、多主体助力的方式进行宣传，有助于精准定位用户、扩大宣传范围。

·线下：

医院---在医院周边投放广告并以二维码形式呈现便于注册；通过医生和护士对病人的推荐引导用户注册，并且可信度高；

红十字会---在红十字成员内部进行推广；

社会---与医学类大中专学校合作，向大学生推广，引导其成为志愿者角色，其获得的志愿者证书可作为学校认定的实践活动证明；

志愿者深入社区进行科普并推广本产品，并现场教学使用；

用户---公益效应发挥作用，用户得到有益帮助可向周边人推广，志愿者的志愿证书激励着更多人参与志愿活动。

·线上：

红十字会---官网和公众号首页投放广告，可信度高，且用户定位更准确；

社会---被救助者事例可能被媒体进行报道，从而提高公众认可度，树立社会形象。
