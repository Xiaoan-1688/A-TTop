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
        <div class="company-name">A & T Top COMPANY LIMITED မှ
ကြိုဆိုပါ၏။</div>
       
       
        
        <!-- 各模块跳转入口（点击直接定位到下方对应内容） -->
        <div style="margin-top: 30px;">
            <h3 style="color: #0066cc;">ကုမ္ပဏီနှင့်သက်ဆိုင်သော module များ</h3>
            <a href="#employee-benefits" class="link-button">→ ကုမ္ပဏီစည်းကမ်းချက်</a><br>
            <a href="#business-process" class="link-button">→ ဝန်ထမ်းအကျိုးခံစားခွင့်မူဝါဒ</a><br>
            <a href="#safety-regulations" class="link-button">→ရုံးပိတ်ရက်အစီအစဥ်များ</a><br>
            <a href="#training-programs" class="link-button">→ ဝန်ထမ်းလေ့ကျင့်ရေးအစီအစဉ်</a>
        </div>
    </div>

    <!-- 1. 员工福利政策模块（锚点ID：employee-benefits） -->
    <div id="employee-benefits" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a> <!-- 返回顶部按钮 -->
        <h2>ကုမ္ပဏီစည်းကမ်းချက်</h2>
        <div class="sub-section">
            <h3> ဝန်ထမ်းများလိုက်နာရန် စည်းကမ်းချက်များ</h3>
     
               
          <p>	ဝန်ထမ်းကဒ်ကိုအလုပ်ချိန်အတွင်းချိတ်ဆွဲရမည်။</p>
<p>အလုပ်ချိန် 8:30ထက်နောက်မကျစေရ၊ အလုပ်တက်/ဆင်း လက်မှတ်ထိုးခြင်းလုပ်ဆောင်ရမည်။ နာရီဝက်ထက်နောက်ကျရင် day ကြေးတစ်ဝက်နှင့်ရက်မှန်ကြေးပြုတ်မည်။</p>
<p>မိမိတာဝန်ကျချိန်မှအပleader၏ခွင့်ပြုချက်မရဘဲ ကုမ္ပဏီဝန်းအပြင်သို့ဝင်ထွက်သွားလာခြင်းမပြုလုပ်ရ။</p>
<p>အလုပ်နေရာမှ မုန့်စားခြင်း၊အိပ်ငိုက်ခြင်း၊အိပ်စက်ခြင်း၊ဖုန်းပြောခြင်း၊ဖုန်းဆော့ခြင်းမပြုလုပ်ရ။</p>
<p>မူးယစ်ဆေးဝါးများကိုလက်ဝယ်ထားရှိခြင်း၊ဖြန့်ဖြူးခြင်းရောင်းချခြင်းနှင့်ကိုယ်တိုင်သံုးစွဲခြင်း မပြုရ။ တွေ့ရှိပါက အလုပ်မှတို့နုတ်ထွက်ခံရပါမည်။</p>
<p>အလုပ်ချိန်အတွင်းစကားမများရ။ စနောက်ကျီစယ်ခြင်းမပြုရ။</p>
<p>ထွက်စာတစ်လကြိုမတင်ဘဲ အနားကပ်မှထွက်စာတင်ထွက်လျှင် ၂၀%ဖြတ်ခံရမည်။ ထွက်စာတစ်လကြိုမတင်လျှင်ဖြစ်စေ၊ ထွက်စာမတင်ဘဲနှုတ်ထွက်လျှင်ဖြစ်စေ လစာလုံးဝရရှိမည်မဟုတ်ပါ။</p>
<p>ခွင့်မဲ့ (၁)ရက်ပျက်တိုင်း သတိပေးစာ (၁)စောင်ထိုးရမည်။ (၃)ခါပြည့်လျှင် (သို့) အကြောင်းမဲ့ခွင့်မဲ့တဆက်တည်း(၃)ရက်ပျက်ကွက်ခြင်းအလုပ်မှနှုတ်ထွက်ရမည်။</p>
အထက်ပါအချက်များသည် Company ၏စည်းကမ်းချက်များကိုကိုးကားထားခြင်းဖြစ်သည်။</p>
            </p>
         <div class="sub-section">
            <h3> အကောင့်လုံခြုံရေး စည်းမျဉ်းများ</h3>
            <p>
                ဝန်ထမ်းများသည် အောက်ပါစည်းကမ်းချက်ကို ကျူးလွန်ကြောင်း ထင်ရှားလျှင် မည်သည့်နစ်နာကြေးအကျိုးခံစားခွင့်ကိုမျှ မခံစားရဘဲ အလုပ်မှရပ်စဲသည်အထိ အပြစ်ပေးနိုင်သည်။
လုပ်ငန်းခွင်မှ နှုတ်ထွက်သွားသည့်နောက်ပိုင်းတွင်လဲ ပြင်ပမှ ကျူးလွန်ပါက ထိရောက်စွာ တရားဉပဒေအရ အရေးယူပါမည်။
မိမိကုမ္ပဏီ၏ အထူးလျှို့ဝှက်ထားရမည့် သတင်းအချက်အလက်များ၊ စာရင်းဇယားများ၊(formula)များ၊နည်းပညာရပ်ဆိုင်ရာ ထုတ်လုပ်မှုလုပ်ငန်းများစသည့် အရေးကြီးသည့်ကိစ္စများကို တစ်ခြားတစ်နေရာသို့ ပေါက်ကြားစေခြင်း၊သတင်းပေးမှုများပြုလုပ်ခြင်း၊ခွင့်ပြုချက်မရဘဲ၊တယ်လီဖုန်း၊ကင်မရာတို့ဖြင့် ဓာတ်ပုံများရိုက်ခြင်း။
            </p>
        </div>
    </div>

    <!-- 2. 业务操作流程模块（锚点ID：business-process） -->
    <div id="business-process" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>ဝန်ထမ်းအကျိုးခံစားခွင့်မူဝါဒ</h2>
        <div class="sub-section">
            <h3>Day Shift Ticket</h3>
            <p>ထောက်ပံ့ကြေး ရုံးတက်ရက်တိုင်းအတွက် တစ်ရက်လျှင် 1000 ခံစားခွင့်ရှိမည် ခွင့် 3 ရက်ယူလျှင် (or) 3 ရက်နောက်ကျလျှင် တစ်လလုံးစာအတွက်ထောက်ပံ့ကြေး မရှိပါ။</p>
            
        </div>
        <div class="sub-section">
            <h3>ဝန်ထမ်းအားလုံး</h3>
           <p>
             Mastery Bonus (အပိုဆုကြေး)အစီအစဉ်လည်းပါဝင်ပါမည်။ ဝန်ထမ်းများ မမျှော်လင့်ထားသည့်အခြေအနေတွင် ပြိုင်ပွဲစတင်မည်။ Mastery Bonus ဆုကြေးသည် ပိုက်ဆံ (or) လက်ဆောင်ဖြစ်နိုင်ပါသည်။
          </p>
            <ol>
                <li>တစ်ပတ် 1ခါ </li>
                <li>10ရက် 1ခါ</li>
                <li>လစဉ် ပြိုင်ပွဲ</li>
              
               <p>
                 အထက်ပါပြိုင်ပွဲများသည် ရည်ညွှန်းချက်တစ်ခုသာဖြစ်ပြီး 
ဆုကြေးနှင့် ပြိုင်ပွဲအချိန် အတိအကျသည် ကုမ္ပဏီ၏ ကြေညာချက်အတိုင်းသာဖြစ်သည်
              </p>
            </ol>
     
    </div>

    <!-- 3. 安全管理规定模块（锚点ID：safety-regulations） -->
    <div id="safety-regulations" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>ရုံးပိတ်ရက်အစီအစဥ်များ</h2>
        <div class="sub-section">
            <h3>G-A</h3>
            <p>
               
            </p>
        </div>
        <div class="sub-section">
            <h3>G-B</h3>
            <p>
                
            </p>
        </div>
        <div class="sub-section">
            <h3>G-C</h3>
            <p>
                
            </p>
        </div>
        
    </div>

    <!-- 4. 员工培训计划模块（锚点ID：training-programs） -->
    <div id="training-programs" class="content-section">
        <a href="#top" class="back-to-top">← 返回顶部</a>
        <h2>ဝန်ထမ်းလေ့ကျင့်ရေးအစီအစဉ်</h2>
        <div class="sub-section">
            <h3>Training</h3>
         
            <ul>
                <li>2ရက်ဆင်း 3ရက်မြောက်တွင် EX ဖြေပေးရမည်</li>
                <li>အများဆုံးတစ်ပတ်အချိန်ပေးမည် အောင်ချက်%မှာ 98%(ဝန်ထမ်းအခြေအနေပေါ်မူတည်၍ Moderation ပေးမည်။)	</li>
                <li>၂ပတ်ပြီးသူများအား နောက်လလစာထဲတွင် 5000ပေါင်းထည့်ပေးမည်</li>
                
            </ul>
        </div>
        <div class="sub-section">
            <h3>ဝန်ထမ်းအားလုံး</h3>
            
            <ul>
                <li>မိမိအလုပ်လုပ်နေသော အကောင့်ကျလျှင် Training ဆင်းပေးရမည်ထိုနေ့အတွက် day ကြေးမရှိ</li>
                <li>အမှားများ /အကောင့်ပိတ် များသူများ သတိပေးစာထိုးရမည် သတိပေးစာ 3ခါပြည့်လျှင် resign တင်ပေးရမည်။</li>
                
            </ul>
      
       
        
    </div>

</body>
</html>
