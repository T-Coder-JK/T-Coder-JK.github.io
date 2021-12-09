# Agile Development in Practice

## Once Upon a Time in Waterfall Land

Before the advent of agile frameworks like Scrum, a product person—the product manager —would typically carry out the market research, compile a market requirements specification, create a business case, put together product roadmap, write a requirements specification, and then hand it off to a project manager. The latter would work with one or more development teams to get the specification implemented. During the development phase, the product manager would be only loosely involved, typically attending a project steering meeting and possibly issuing change requests. Otherwise, the individual would hope that the requirements were implemented as specified. Only once the product was close to being finished would the product manager return to the project and prepare the release of the product. This sequential, waterfall-based approach used to work when there was little change and innovation, when product managers could correctly predict what the users needed and describe the detailed product functionality upfront. But it is less suited to create complex digital products.

## The Brave New Agile World

As agile practices have become more widely adopted, the processes used to develop products have significantly changed: Product people and development teams now tend to collaborate much more closely. Dev teams have become cross-functional consisting of UX designers, architects, programmers, testers, and other roles. Products are developed using iterative-incremental processes like Scrum. Requirements are no longer detailed and frozen before development starts but they emerge. An increasing number of organizations have moved away from organizing around projects and have started to embrace a product-led approach.

**Early user feedback, frequent solution validation:** We now have the ability to collect early and frequent user and customer feedback, which helps us validate our ideas and update our plans accordingly. This has increased the chances of creating a product with the right UX and the right features. 

**Reduced time-to-market:**We can now release new products and features more quickly. This is enabled by a closer, ongoing collaboration with cross-functional development teams, shifting from written documentation to face-to-face conversations, and using techniques such as user stories that reduce overhead—when applied correctly. 

**Better product quality and improved adaptability:** The quality of our products has improved through the application of agile development practices like emergent design, test-driven development, and continuous integration. This has allowed us to adapt the product more quickly and to respond to user feedback more easily. 

**Better requirements:** As product people, we are no longer solely responsible for coming up with the correct requirements. Instead, the dev team members actively participate in the product backlog refinement work and help us identify the necessary changes and capture new product backlog items. This leverages the team members’ creativity and expertise, creates a shared understanding, fosters collective ownership, improves the quality of the requirements, and ultimately results in better products. 

**Transparent development progress:** We can see the development progress more clearly and make corrections early if required: The progress is now based on working software rather than a detailed, Gantt chart-based project plan. This mitigates the risk of discovering late that the product cannot be shipped on time or that some features were implemented incorrectly. 

**Improved alignment:** Stakeholders and development teams are now better aligned through the use of regular collaborative workshops like sprint reviews. This creates a shared understanding and leads to greater commitment: Asking people about their perspectives and involving them in the process of making product decisions increases the likelihood that the individuals will support the decisions.

**Motivated productive teams:** Last but not least, self-organizing development teams tend to be more motivated and productive compared to traditional ones, as they are able to determine themselves how much work can be done in a given period, decide who carries out a specific piece of work, and agree on how the team members collaborate.

## Old and New Product Management Challenges

While agile methods have given us plenty of benefits, a number of product management challenges still persist. These were not caused by agile practices, as far as I can tell. Agile has made them more visible, though, and it has exacerbated some of them. Let’s look at the key challenges that remain.

**Lack of empowerment:** When coining the Scrum terms, Ken Schwaber and Jeff Sutherland chose the term product owner instead of product manager in order to emphasize the level of authority and empowerment a product person requires—especially in an agile context where collaboration is valued, and stakeholders and dev teams regularly contribute to product decisions. 

Unfortunately, a lack of empowerment is still a common issue: Product people often don’t have the necessary authority to make strategic product decision, shape the strategy, and own the roadmap. Consequently, they are in danger of playing a tactical product role and being product backlog managers and user story writers rather than owning the product in its entirety and being able to maximize the value it creates.

**Confusion about roles and responsibilities:** Even 20 years after the Manifesto for Agile Software Development was conceived, agile roles like product owner and Scrum Master are not always clearly understood, let alone effectively applied. As indicated above, product owners are sometimes mistaken for product backlog managers and stakeholder pleasers instead of the individuals who are in charge of a product and whose decisions the entire organization must respect, as the Scrum Guide puts it.

**Lack of direct interaction with users and customers:** Customer collaboration is one of the four values in the agile manifesto. Nevertheless, it’s not uncommon for me to meet product people who don’t have direct access to users and customers. Instead, they solely rely on quantitative data and feedback from sales, which makes it hard to empathize with the users and customers and to fully understand their needs. This, in turn, reduces the chances of offering a product that does a great job for its target audience and generates the desired business benefits. 

**Product discovery and product strategy poorly practiced:** The most beautiful user stories are useless if it’s not clear who the users are and why they would want to use the product. Acquiring this information requires focused product discovery and strategy work. Unfortunately, product discovery and strategy aren’t always effectively practiced. This is not helped by the fact that agile approaches like Scrum do not offer any tools and techniques to help product owners understand if a product should be developed. Fortunately, a number of tools and techniques have emerged in recent years that help product people with their product discovery and strategy work including product vision board and GO product roadmap. 

**Lack of sustainable pace:** “The sponsors, developers, and users should be able to maintain a constant pace indefinitely,” states the Manifesto for Agile Software Development. Ironically, working at a healthy, sustainable pace can be particularly challenging in an agile context: Product people have to regularly interact with development teams in order to update the product backlog, agree on sprint goals, answer questions, and provide feedback on product increments in addition to all the other product management duties. Being overworked, however, has a negative impact on our productivity and mental health.

------

# 敏捷开发中的重要会议

## 敏捷三要素

1. 相互信任
2. 共同远景
3. 频繁小批：将工作拆分成尽可能小的粒度，分别进行交付。之后对已交付的任务根据反馈进行快速的迭代。 优势：加快交付的效率。 提高所开发产品的质量。

## 持续集成(Continuous Integration)

**核心**：

1. 必须每次提交都要出发构建。

2. 每次提交必须基于上次的成功构建。

## 迭代中的沟通计划

1. **沟通计划的主要实践**
    - IPM迭代计划会议
        
        Iteration Planning Meeting: 关注计划， 与客户一起调整迭代计划，关注任务优先级。
        
    - IKM迭代开始会议
        
        Iteration Kickoff Meeting:团队内部明确迭代的愿景和短期目标 
        
    - Standup Meeting每日站会
        
        站会中应该更多的关注进度，障碍，新知，及是否对现有计划做出调整。
        
    - Retrospective迭代回顾会议
        
        团队成员对上个迭代中的优劣进行总结，分析和提升
        
    - Showcase迭代成果展示
        
        对外用于客户理解项目进度，控制开发计划，对内用于团队内部的检视和改进
        
2. **沟通计划的作用**
    - 确保工作时间
        
        DEV的理想工作时间（沟通10%-15%， 工作85%-90%）
        
    - 建立工作节奏
        
        确立好工作节奏，使得事件的发生可预期.
        
3. **两个循环**（内部，外部）
    - **IPM** → Showcase 对外循环，用于客户理解项目进度，控制开发计划
        
        IPM 会议中的主要角色Business Analyst ， Tech Lead，Project Manager以及客户. 其他组员应该视情况出席。应该以会议的效率为优先。
        
        1. 基于客户对于showcase的反馈，与客户确认和调整新的Story.
        2. 对于已有的story确认优先级，最好给客户提供一个已有的高，中，低优先级的分类作为参考系。这样可以更加客观的给新产生的story进行优先级分类。给每一个story进行estimation，使用户明确新加入的story所产生的成本。
        
    - **IKM** → Showcase → Retrospective 对内循环， 用于团队内部的检视和改进
        
        IKM需要向全体团队成员明确下个Iteration的目标。 全面介绍新的user story的user    journey。不停的向团队成员重复项目最重要的宏观上下文和user journey，确保每个成员都能一直把握这些内容。 IKM需要控制时间，避免过于细节。在IKM上关注项目宏观的理解， 将细节问题留在会后解决澄清。
        
    
4. **ShowCase**
    
    ShowCase是每个迭代中的非常重要的验收环节。它的主要功能有两点： 首先它是对与上个迭代工作的呈现和确认。其次，它是一个与PO沟通和收集PO反馈的重要时间节点。它的一个核心目标是根据迭代计划和团队承诺回顾迭代的进度，并展现出团队达成的共识及向着目标前进的努力。
    
    关注点:
    
    - 邀请适合的参与人。
        
        确定能够真正提供验收意见的PO，如果这些PO无法参加，考虑改期或者取消。
        
    - 做好充分的准备。
        
        考虑失败的比例，尽可能的做好充分准备。
        
    - 展示价值胜过功能。因为功能只是呈现价值的一种方式
    - 展示工作在正确的道路和方向上。对于很多有很高不确定性的工作来讲，一次把事情做对是有些奢望的，所以在工作没有能够完全按照预期完成的时候，展现工作在一个正确的道路上也是同样有价值的事情
    - 寻求反馈与验收
        
        **Sign off** or **Push back** 无论是正向或者负面的反馈都是我们在实践Agile是期望的反馈
        
    
5. **Retrospective**
    
    本质上是Brainstorm的一种形式,  使用整个团队的力量，对当前迭代执行过程进行反思，提升自我认知，围绕认知进行持续的改进。 **Retro**可以有多种形式，可以按照团队所处的具体情况来选择合适的**Retro**形式。 
    
    - 避免相互指责
    - 需要参与者彼此开诚布公
    
    如何获得有针对性改进的Action, 通过团队成员讨论后获得Action，之后对所获得的Action进行票选，明确所需执行Action的成本。 将Action落实到团队成员，并且检查上次Action的执行结果。
    
    对接下来一个迭代的时间压力要有预估，参照预估结果来对成员可被允许投票的数量进行限定。可以容纳越多Action，那么团队每个成员也应该相应增加可投票的数量。
    
6. **Daily** **Stand-up**
    
    每天固定时间，给所有团队成员提供一个，精简高效的沟通窗口。无论站会发生在一天的什么时间段，都要尽量的压缩时长。沟通需要帮助的问题，同步开发状态。尽可能的精简所要沟通的内容，压缩发言的时间长度。不要展开问题和解决方案细节，可留在会后跟团队成员进行点对点的沟通。
    
