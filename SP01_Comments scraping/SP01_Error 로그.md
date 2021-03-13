# Error 로그

## ElementNotVisibleException

TypeError: 'WebElement' object is not iterable

**1. find_element_by_class_name으로 추출한 것을 for문으로 돌려 출력하려고 했을 때 발생**

**2. 답글 보기 내 더 보기 버튼을 누르기 위해 find_element_by_class_name('link_fold').click()을 실행했을 때 발생**



## NoSuchElementException 

Message: no such element: Unable to locate element: {"method":"class name","selector":"num_txt"}
  (Session info: chrome=88.0.4324.190)
  (Driver info: chromedriver=2.37.544315 (730aa6a5fdba159ac9f4c1e8cbc59bf1b5ce12b7),platform=Windows NT 10.0.19041 x86_64)

**find_element_by_class_name으로 추출한 것에서 다시 find_element_by_class_name로 element를 꺼내려고 했을 때 발생**



## WebDriverException 

Message: unknown error: Element <button class="reply_count #reply ?c_title=%EB%8B%B5%EA%B8%80" aria-expended="false" data-tiara-action-name="답글목록_열기" data-reactid=".0.0.0.3.3.$645940130.0.3.0.0">...</button> is not clickable at point (38, 477). Other element would receive the click: <div class="reply_wrap" data-reactid=".0.0.0.3.3.$645941580.0.4">...</div>
  (Session info: chrome=88.0.4324.190)
  (Driver info: chromedriver=2.37.544315 (730aa6a5fdba159ac9f4c1e8cbc59bf1b5ce12b7),platform=Windows NT 10.0.19041 x86_64)

**find_element_by_class_name으로 추출한 답글이 존재하는 답글 보기 element를 click()으로 클릭할 때 발생**



## NewConnectionError 

<urllib3.connection.HTTPConnection object at 0x0000029724177940>: Failed to establish a new connection: [WinError 10061] 대상 컴퓨터에서 연결을 거부했으므로 연결하지 못했습니다

MaxRetryError: HTTPConnectionPool(host='127.0.0.1', port=): Max retries exceeded with url: /session/c31957f44c7b7ead26ad1ed516451be4/elements (Caused by NewConnectionError('<urllib3.connection.HTTPConnection object at 0x0000029723DE6A90>: Failed to establish a new connection: [WinError 10061] 대상 컴퓨터에서 연결을 거부했으므로 연결하지 못했습니다'))

**답글 보기 클릭 이슈를 해결하기 위해 뉴스 기사 한 페이지만 샘플로 크롤링해 보려 시도했을 때 발생**



## StaleElementReferenceException 

Message: stale element reference: element is not attached to the page document
  (Session info: chrome=89.0.4389.82)
  (Driver info: chromedriver=2.37.544315 (730aa6a5fdba159ac9f4c1e8cbc59bf1b5ce12b7),platform=Windows NT 10.0.19041 x86_64)

**ActionChains(driver).move_to_element(r).click(r).perform()으로 답글 보기 클릭 시도를 했을 때 발생**