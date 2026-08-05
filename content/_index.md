---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-08-04
type: landing

sections:
  - block: markdown
    id: hero
    content:
      title: ''
      text: |
        <div class="apple-hero-img-container">
          <img src="/apple-hero-product.png" alt="Hero Product" width="400" class="product-shadow">
        </div>
        <div class="text-center mt-6">
          <h1 class="apple-display" style="font-size: 3.5rem; margin-bottom: 0.5rem;">
            박기현
          </h1>
          <p style="font-size: 1.5rem; color: #1d1d1f; margin-bottom: 2rem; font-weight: 400;">
            하나님의 마음을 품고 밝은 세상을 만들어 갑니다.
          </p>
          <div class="flex justify-center gap-4 flex-wrap">
            <a class="btn btn-primary" href="#contact">강연/교육 문의하기</a>
            <a class="btn btn-outline-primary" href="#projects-lectures">활동 및 강연 살펴보기</a>
          </div>
        </div>
    design:
      css_class: 'apple-tile-parchment'
      columns: '1'

  - block: markdown
    id: about
    content:
      title: ''
      text: |-
        <div class="text-center mx-auto" style="max-width: 800px;">
          <h2 class="apple-display" style="font-size: 2.5rem; margin-bottom: 1.5rem;">소개</h2>
          <p style="font-size: 1.25rem; line-height: 1.6; margin-bottom: 2rem; font-weight: 400;">
            "저는 하나님의 마음을 품은 사람들을 양성하고, 선한 사람들의 따뜻한 네트워크에 AI 기술이라는 유용한 도구를 더해 나갑니다. 이를 통해 선교의 지경을 넓히고, 세상 곳곳을 밝게 비추는 사역의 여정을 여러분과 함께 걸어가고 싶습니다."
          </p>
          <ul style="font-size: 1.1rem; line-height: 2; list-style: none; padding: 0;">
            <li>🌱 <strong style="color: #ffffff;">사람 양성</strong></li>
            <li>🤝 <strong style="color: #ffffff;">선한 연대</strong></li>
            <li>💻 <strong style="color: #ffffff;">AI 기술 선교</strong></li>
          </ul>
        </div>
    design:
      css_class: 'apple-tile-dark'
      columns: '1'

  - block: markdown
    id: projects-lectures
    content:
      title: '🚀 활동 및 강연'
      subtitle: 'JIWU Mission Network & 편한IT'
      text: |-
        ## 활동 / 프로젝트 (Projects)
        
        *   **AI & 디지털 역량 강화:** 실생활과 업무에 바로 적용할 수 있는 실용적인 교육 (AI 활용 강좌, Notion 워크플로우 구축, 웹사이트 제작 교육 등)
        *   **스마트 사역 행정 지원:** 복잡한 기술이 아닌 유용한 IT 도구를 활용해 단체와 모임의 행정을 효율적으로 돕는 실무 지원
        *   **JIWU Mission Network 사역:** 미디어와 네트워크를 통한 복음 전파 (문서 선교, 인터넷 선교, 작은 교회 및 선교사를 위한 맞춤형 행정 지원)

        <br>

        ## 강연 / 서비스 안내 (Lectures)

        ### [강좌 1] 사역과 업무를 가볍게 돕는 스마트 행정 (Notion & 협업 툴)
        *   **누구를 위한 강의인가요?** 행정 효율을 높이고 싶은 목회자, 선교사, 비영리 활동가
        *   **무엇을 얻을 수 있나요?** MS Teams와 Notion을 연동해 복잡한 업무와 문서 관리를 줄이고, 본질적인 사역에 더 집중할 수 있는 나만의 워크플로우를 완성합니다.

        ### [강좌 2] 일상을 바꾸는 실용적인 AI 활용법 (꿈골 지식나눔)
        *   **누구를 위한 강의인가요?** AI를 실제 생활과 업무에 바로 적용해 보고 싶은 누구나
        *   **무엇을 얻을 수 있나요?** 내 컴퓨터 환경(Local AI)에 맞는 최적의 세팅부터 AI 챗봇 비교, 실전 프롬프트 작성법을 익혀 실생활의 문제들을 해결합니다.

        ### [강좌 3] 비용 부담 없이 시작하는 맞춤형 웹사이트 구축
        *   **누구를 위한 강의인가요?** 예산과 IT 지식이 부족한 작은 교회 및 단체
        *   **무엇을 얻을 수 있나요?** 전문 지식이 없어도, 꼭 필요한 기능을 담은 웹사이트를 직접 구축하고 운영할 수 있는 실질적인 가이드를 제공합니다.

        <br>
        
        <a href="https://youtube.com/ccumgol" target="_blank" class="btn btn-primary">유튜브에서 무료로 배우기</a>

    design:
      columns: '1'

  - block: collection
    id: blog
    content:
      title: 📝 블로그 / 칼럼
      subtitle: 'AI 실전 매뉴얼부터 사역과 일상 기록까지'
      text: ''
      page_type: post
      count: 10
      filters:
        folders:
          - blog
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    id: contact
    content:
      title: 📬 문의 및 연락처
      subtitle: ''
      text: |-
        강연 요청, 사역 동참 및 작은 교회 행정 지원 문의는 아래 이메일이나 카카오톡으로 남겨주시면 정성껏 답변해 드리겠습니다.
        
        원활한 소통을 위해 메일 전송 시 아래 정보를 포함해 주세요.
        * [이름 / 소속(교회 및 단체명) / 연락처 / 문의 내용]

        ---
        **📧 Email:** [ccumgol@gmail.com](mailto:ccumgol@gmail.com)  
        **💬 카카오톡 문의:** [카카오톡 채널](#)
    design:
      columns: '2'
---
