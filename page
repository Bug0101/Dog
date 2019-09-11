from poium import Page,PageElement

class LoginPage(Page):
    """管家公登录Page类"""
    login_frame = PageElement(class_name='choice-box',describe="一代登录框")
    username = PageElement(id_='UserName',describe="登录用户名")
    password = PageElement(id_='PassWord',describe="登录密码")
    code = PageElement(id_='UserCode',describe="验证码")
    login_button = PageElement(xpath="//*[@id='LoginForm']/button",describe="登录按钮")

class ChangeDogPage(Page):
    """硬换软Page类"""
    hh_buy_button = PageElement(xpath="/html/body/div[2]/div/div[3]/div/div[10]/div/div/div[2]/div/a[1]",describe="购买辉煌按钮")
    hh_change_dog_manage = PageElement(id_='925',describe="硬狗换软狗管理")
    hh_change_dog_apply = PageElement(xpath="//div[@id='sidebar']/ul/li[14]/ul/li[1]/a",describe="换狗申请")
    dog_number = PageElement(xpath="//*[@id='DogNo']",describe="狗号")
    card_number = PageElement(xpath="//*[@id='CardNumber']",describe="卡号")
    company_name = PageElement(xpath="//*[@id='CompanyName']",describe="公司名称")
    agent_name = PageElement(xpath="//*[@id='AgentName']",describe="联系人名字")
    mobile_number = PageElement(xpath="//*[@id='MobileTel']",describe="手机号")
    tel_number = PageElement(xpath="//*[@id='Tel1']",describe="座机号")
    email = PageElement(xpath="//*[@id='Email']",describe="邮箱")
    agent_code = PageElement(xpath="//*[@id='AgentCode']",describe="二级代理商编号")
    address = PageElement(xpath="//*[@id='Address']",describe="地址")
    remarks = PageElement(xpath="//*[@id='Remarks']",describe="备注")
    submit_button = PageElement(xpath="//*[@id='Frorm']/div/div[5]/div/button[1]",describe="确认提交按钮")
