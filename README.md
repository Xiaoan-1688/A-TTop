<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="A & T Top COMPANY LIMITED - 缅甸仰光北奥卡拉帕镇区企业">
    <meta name="keywords" content="A & T Top COMPANY LIMITED, 缅甸公司, 仰光企业">
    <meta name="author" content="A & T Top COMPANY LIMITED">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A & T Top COMPANY LIMITED</title>
    <style>
        /* 整体页面样式设置 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            scroll-behavior: smooth; /* 平滑滚动效果，点击锚点不生硬跳转 */
        }
        /* 头部区域样式 */
        header {
            background-color: white;
            border-bottom: 2px solid #0066cc;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky; /* 头部固定在顶部，滚动时不消失 */
            top: 0;
            z-index: 100;
        }
        /* 公司名称部分样式 */
        .company-name {
            font-size: 24px;
            font-weight: bold;
            color: #0066cc;
            line-height: 1.2;
        }
        /* 联系方式区域样式 */
        .contact-info {
            display: flex;
            align-items: center;
            gap: 25px;
            flex-wrap: wrap;
        }
        .contact-item {
            display: flex;
            align-items: center;
            flex-wrap: wrap;
        }
        .contact-item img {
            width: 24px;
            height: 24px;
            margin-right: 8px;
        }
        .contact-item span {
            font-size: 14px;
            color: #666;
            line-height: 1.5;
        }
        /* 链接样式（跳转模块的按钮） */
        .link-button {
            color: #0066cc;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
            display: inline-block;
            margin: 8px 0;
        }
        .link-button:hover {
            text-decoration: underline;
        }
        /* 各模块内容样式（员工福利、业务流程等） */
        .content-section {
            max-width: 1200px;
            margin: 30px auto;
            padding: 25px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05); /* 轻微阴影，更显层次感 */
        }
        .content-section h2 {
            color: #0066cc;
            margin-top: 0;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
        }
        /* 子模块样式（如福利政策中的“基本福利”“奖金制度”） */
        .sub-section {
            margin-bottom: 25px;
            padding: 15px;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .sub-section h3 {
            color: #333;
            margin-bottom: 10px;
            font-size: 18px;
        }
        .sub-section p, .sub-section ul {
            color: #666;
            line-height: 1.6;
            font-size: 16px;
        }
        .sub-section ul {
            padding-left: 20px;
        }
        .sub-section li {
            margin-bottom: 8px;
        }
        /* 返回顶部按钮 */
        .back-to-top {
            display: inline-block;
            padding: 8px 15px;
            background-color: #0066cc;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            margin: 10px 0;
        }
        .back-to-top:hover {
            background-color: #0052a3;
        }
        /* 手机端适配 */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                gap: 15px;
                padding: 15px 20px;
            }
            .contact-info {
                flex-direction: column;
                align-items: flex-start;
            }
            .content-section {
                padding: 15px;
                margin: 20px auto;
            }
        }
    </style>
</head>
<body>
    <!-- 头部（固定在顶部） -->
    <header>
        <div class="company-name">A & T Top COMPANY LIMITED</div>
        <div class="contact-info">
            <div class="contact-item">
                <img src="https://p.kindpng.com/picc/s/207-2074088_transparent-phone-call-png-call-telephone-icon-vector.png" alt="电话图标">
                <span>09689866134</span>
            </div>
            <div class="contact-item">
                <img src="https://cdn-icons-png.flaticon.com/512/6903/6903405.png" alt="地址图标">
                <span>Hta Ward, Sudamma Road, Corner of Naykar Street, North Oaklapalar Township, Yangon</span>
            </div>
            <div class="contact-item">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732208.png" alt="邮箱图标">
                <span>Attopcompany37@gmail.com</span>
            </div>
        </div>
    </header>

    <!-- 首页核心内容（包含各模块跳转入口） -->
    <div class="content-section">
        <div class="company-name">ကျွန်ုပ်တို့၏ A&T မိသားစုတွင် ပါဝင်ရန် ကြိုဆိုပါသည်။</div>
        <h2>账号</h2>
        <p>
            A&T Top Co.,Ltdတွင် အလုပ်လုပ်ကိုင်နေသော ဝန်ထမ်းများ မိမိရရှိထားသော အကောင့်များအားအလုပ်ထွက်ပြီးသည်အထိ 
            ထိုအကောင့်များ ပြဿနာတစ်စုံတစ်ရာရှိပါက ကိုယ်တိုင်တာဝန်ယူဖြေရှင်းပေးရမည်ကို ခံဝန်လတ်မှတ်ထိုးပါသည်။ 
        </p>
        
        <!-- 各模块跳转入口（点击直接定位到下方对应内容） -->
        <div style="margin-top: 30px;">
            <h3 style="color: #0066cc;">公司相关模块</h3>
            <a href="#employee-benefits" class="link-button">→ 员工福利政策</a><br>
            <a href="#business-process" class="link-button">→ 业务操作流程</a><br>
            <a href="#safety-regulations" class="link-button">→ 安全管理规定</a><br>
            <a href="#training-programs" class="link-button">→ 员工培训计划</a>
        </div>
    </div>

    <!-- 1. 员工福利政策模块（锚点ID：employee-benefits） -->
    <div id="employee-benefits" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a> <!-- 返回顶部按钮 -->
        <h2>员工福利政策</h2>
        <div class="sub-section">
            <h3>1. 基本福利</h3>
            <p>
                公司为所有正式员工提供完善的基本福利，包括医疗保险、年度体检、带薪年假等。
                员工入职满一年后即可享受15天带薪年假，服务年限每增加一年，年假增加1天，最多不超过30天。
            </p>
        </div>
        <div class="sub-section">
            <h3>2. 奖金制度</h3>
            <p>
                公司实行绩效奖金制度，根据员工个人及公司整体业绩表现，每年发放1-2次奖金。
                对于表现优异的员工，公司将给予额外奖励及晋升机会。
            </p>
        </div>
        <div class="sub-section">
            <h3>3. 培训与发展</h3>
            <p>
                公司重视员工成长，为员工提供各类专业培训课程及外部学习机会。
                表现优秀的员工将有机会参与海外培训及交流项目。
            </p>
        </div>
        <div class="sub-section">
            <h3>4. 其他福利</h3>
            <p>
                公司为员工提供节日福利、生日福利、团队建设活动等。
                工作满三年的员工可享受公司提供的住房补贴或交通补贴。
            </p>
        </div>
    </div>

    <!-- 2. 业务操作流程模块（锚点ID：business-process） -->
    <div id="business-process" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>业务操作流程</h2>
        <div class="sub-section">
            <h3>1. 客户接洽流程</h3>
            <p>客户接洽遵循以下步骤：</p>
            <ol>
                <li>初步接触：记录客户基本信息及需求</li>
                <li>需求分析：与客户深入沟通，明确具体需求</li>
                <li>方案制定：根据客户需求制定初步方案</li>
                <li>方案沟通：与客户讨论方案并进行调整</li>
                <li>合作确认：双方达成一致，签订合作协议</li>
            </ol>
        </div>
        <div class="sub-section">
            <h3>2. 项目执行流程</h3>
            <p>项目执行遵循以下步骤：</p>
            <ol>
                <li>项目启动：召开项目启动会议，明确责任分工</li>
                <li>进度规划：制定详细的项目进度表</li>
                <li>执行实施：按照计划推进项目各项工作</li>
                <li>定期汇报：每周向客户汇报项目进展情况</li>
                <li>问题处理：及时解决项目中出现的问题</li>
                <li>项目验收：完成后由客户进行验收</li>
            </ol>
        </div>
        <div class="sub-section">
            <h3>3. 售后服务流程</h3>
            <p>售后服务遵循以下步骤：</p>
            <ol>
                <li>定期回访：项目完成后定期回访客户使用情况</li>
                <li>问题响应：收到客户反馈后24小时内响应</li>
                <li>问题解决：根据问题性质提供解决方案</li>
                <li>满意度调查：解决问题后进行客户满意度调查</li>
                <li>总结改进：根据反馈持续改进服务质量</li>
            </ol>
        </div>
    </div>

    <!-- 3. 安全管理规定模块（锚点ID：safety-regulations） -->
    <div id="safety-regulations" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>安全管理规定</h2>
        <div class="sub-section">
            <h3>1. 工作场所安全</h3>
            <p>
                所有员工必须遵守工作场所安全规定，保持工作区域整洁有序。
                禁止在工作场所吸烟，严禁携带易燃易爆物品进入办公区域。
                消防器材定期检查，所有员工必须熟悉消防器材的使用方法和紧急疏散路线。
            </p>
        </div>
        <div class="sub-section">
            <h3>2. 设备使用安全</h3>
            <p>
                员工在使用公司设备前必须接受相关培训，严格按照操作规程使用。
                电气设备出现故障时，应立即停止使用并通知维修人员，严禁私自拆卸维修。
                定期对设备进行维护保养，确保设备正常安全运行。
            </p>
        </div>
        <div class="sub-section">
            <h3>3. 数据安全管理</h3>
            <p>
                员工必须妥善保管公司数据资料，不得随意拷贝或外传。
                电脑设置强密码并定期更换，离开工作岗位时应锁定电脑。
                发现数据安全隐患或泄露情况，应立即向主管报告。
            </p>
        </div>
        <div class="sub-section">
            <h3>4. 紧急情况处理</h3>
            <p>
                发生紧急情况时，保持冷静并按照应急预案采取相应措施。
                紧急联系电话应张贴在显眼位置，所有员工必须熟记。
                发生事故或安全隐患，应立即报告直接主管并记录相关情况。
            </p>
        </div>
    </div>

    <!-- 4. 员工培训计划模块（锚点ID：training-programs） -->
    <div id="training-programs" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>员工培训计划</h2>
        <div class="sub-section">
            <h3>1. 新员工入职培训</h3>
            <p>新员工入职后需参加以下培训：</p>
            <ul>
                <li>公司文化与规章制度培训（1天）</li>
                <li>岗位技能基础培训（3-5天）</li>
                <li>安全知识培训（半天）</li>
                <li>业务流程培训（2天）</li>
                <li>导师带教（1个月）</li>
            </ul>
        </div>
        <div class="sub-section">
            <h3>2. 在职员工技能提升培训</h3>
            <p>在职员工可参加以下培训：</p>
            <ul>
                <li>专业技能进阶课程（每季度）</li>
                <li>管理能力培训（针对主管级以上员工）</li>
                <li>行业新知识与趋势培训（每月）</li>
                <li>语言培训（英语及当地语言）</li>
                <li>计算机与办公软件技能培训</li>
            </ul>
        </div>
        <div class="sub-section">
            <h3>3. 培训评估与反馈</h3>
            <p>
                所有培训结束后将进行评估，包括笔试、实操或项目考核等形式。
                员工需对培训内容和讲师进行反馈，公司将根据反馈持续改进培训质量。
                培训成绩将作为员工绩效考核和晋升的参考依据之一。
            </p>
        </div>
        <div class="sub-section">
            <h3>4. 外部培训机会</h3>
            <p>
                公司每年将选派表现优秀的员工参加外部专业培训课程或行业会议。
                工作满两年且表现突出的员工有机会参与海外培训项目。
                参加外部培训的员工需在培训后向团队分享所学知识。
            </p>
        </div>
    </div>

</body>
</html>
