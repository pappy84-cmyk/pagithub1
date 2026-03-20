# pagithub1
new account for desktop
from playwright.sync_api import Page, expect


def test_verifyPageUrl(page:Page):
    page.goto('https://www.google.com')
    expect(page).to_have_url('https://www.google.com')
