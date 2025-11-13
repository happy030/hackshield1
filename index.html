<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>학교 분실물 검색 시스템</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; }
    body {
      font-family: 'Noto Sans KR', system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      margin: 0;
      background: #f5f7fb;
      color: #222;
    }
    header {
      background: #3f51b5;
      color: #fff;
      padding: 16px 20px;
      font-size: 20px;
      font-weight: 600;
    }
    main {
      max-width: 1100px;
      margin: 20px auto 40px;
      padding: 0 16px;
    }
    h2 {
      margin-top: 0;
      font-size: 20px;
    }
    section {
      background: #fff;
      border-radius: 10px;
      padding: 16px 18px 20px;
      margin-bottom: 18px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.06);
    }
    .section-sub {
      font-size: 13px;
      color: #666;
      margin-bottom: 10px;
    }
    form {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 10px 16px;
      align-items: flex-start;
    }
    label {
      display: block;
      font-size: 13px;
      margin-bottom: 4px;
      color: #444;
    }
    input[type="text"],
    input[type="date"],
    select,
    textarea {
      width: 100%;
      padding: 7px 9px;
      border-radius: 6px;
      border: 1px solid #c7cbe6;
      font-size: 13px;
      outline: none;
    }
    textarea {
      resize: vertical;
      min-height: 60px;
    }
    input:focus, select:focus, textarea:focus {
      border-color: #3f51b5;
      box-shadow: 0 0 0 2px rgba(63,81,181,0.18);
    }
    .full-width {
      grid-column: 1 / -1;
    }
    .btn {
      display: inline-block;
      padding: 8px 16px;
      border-radius: 8px;
      border: none;
      font-size: 14px;
      cursor: pointer;
      transition: transform 0.05s ease, box-shadow 0.05s ease, background 0.15s ease;
    }
    .btn-primary {
      background: #3f51b5;
      color: #fff;
      box-shadow: 0 2px 4px rgba(63,81,181,0.3);
    }
    .btn-primary:hover {
      background: #3646a0;
    }
    .btn-primary:active {
      transform: translateY(1px);
      box-shadow: 0 1px 2px rgba(63,81,181,0.4);
    }
    .btn-ghost {
      background: transparent;
      color: #3f51b5;
      border: 1px solid #c7cbe6;
    }
    .btn-ghost:hover {
      background: #edf0ff;
    }
    .search-bar {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 10px;
      align-items: center;
    }
    .search-bar select,
    .search-bar input[type="text"] {
      max-width: 240px;
    }
    .counter {
      font-size: 13px;
      color: #555;
      margin-bottom: 6px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 12px;
    }
    .card {
      background: #fafbff;
      border-radius: 10px;
      padding: 10px;
      border: 1px solid #e0e3f4;
      display: flex;
      gap: 10px;
      min-height: 110px;
    }
    .card-thumb {
      flex: 0 0 90px;
      height: 90px;
      border-radius: 8px;
      overflow: hidden;
      background: #e3e6f5;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 11px;
      color: #666;
    }
    .card-thumb img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
    .card-body {
      flex: 1;
      font-size: 13px;
    }
    .card-body .title-line {
      font-weight: 600;
      margin-bottom: 3px;
    }
    .badge {
      display: inline-block;
      padding: 2px 6px;
      border-radius: 999px;
      font-size: 11px;
      margin-right: 4px;
      background: #e1e5ff;
      color: #333;
    }
    .muted {
      color: #777;
      font-size: 12px;
    }
    .no-result {
      font-size: 13px;
      color: #777;
      padding: 6px 0;
    }
    @media (max-width: 600px) {
      header {
        font-size: 17px;
      }
      .card {
        flex-direction: column;
      }
      .card-thumb {
        width: 100%;
        height: 140px;
      }
    }
  </style>
</head>
<body>
<header>
  🏫 학교 분실물 검색 시스템 (프로토타입)
</header>

<main>
  <!-- 분실물 등록 섹션 -->
  <section id="register-section">
    <h2>1. 분실물 등록</h2>
    <p class="section-sub">
      교사나 담당 학생이 새 분실물을 등록하는 영역입니다. 이미지 파일은 파일명만 입력하고, 실제 사진은 같은 폴더 안에 보관하면 됩니다.
    </p>

    <form id="register-form">
      <div>
        <label for="category">카테고리</label>
        <select id="category" required>
          <option value="">선택하세요</option>
          <option>우산</option>
          <option>의류</option>
          <option>학용품</option>
          <option>전자기기</option>
          <option>카드/지갑</option>
          <option>기타</option>
        </select>
      </div>

      <div>
        <label for="color">색깔</label>
        <input id="color" type="text" placeholder="예: 검정, 파랑" />
      </div>

      <div>
        <label for="brand">브랜드 / 로고</label>
        <input id="brand" type="text" placeholder="예: Nike, Adidas, 학교 로고 등" />
      </div>

      <div>
        <label for="location">발견 장소</label>
        <input id="location" type="text" placeholder="예: 2층 복도, 체육관, 급식실" />
      </div>

      <div>
        <label for="dateFound">발견 날짜</label>
        <input id="dateFound" type="date" />
      </div>

      <div class="full-width">
        <label for="description">기타 특징</label>
        <textarea id="description" placeholder="예: 이름 스티커 붙어 있음, 손잡이에 흰 줄무늬 등"></textarea>
      </div>

      <div class="full-width">
        <label for="imageName">이미지 파일명 (선택)</label>
        <input id="imageName" type="text" placeholder="예: umbrella1.jpg (같은 폴더에 저장)" />
      </div>

      <div class="full-width">
        <button type="submit" class="btn btn-primary">등록하기</button>
        <button type="button" class="btn btn-ghost" id="reset-btn">폼 초기화</button>
      </div>
    </form>
  </section>

  <!-- 검색 섹션 -->
  <section id="search-section">
    <h2>2. 분실물 검색</h2>
    <p class="section-sub">
      카테고리와 키워드(색, 브랜드, 장소, 특징 등)를 조합해서 원하는 분실물을 빠르게 찾을 수 있습니다.
    </p>

    <div class="search-bar">
      <div>
        <label for="searchCategory">카테고리</label><br />
        <select id="searchCategory">
          <option value="all">전체</option>
        </select>
      </div>
      <div>
        <label for="keyword">키워드</label><br />
        <input id="keyword" type="text" placeholder="색, 브랜드, 장소, 특징 등으로 검색" />
      </div>
      <div>
        <button id="searchBtn" class="btn btn-primary" type="button">검색</button>
      </div>
      <div>
        <button id="clearBtn" class="btn btn-ghost" type="button">필터 초기화</button>
      </div>
    </div>

    <div class="counter" id="resultCounter"></div>
    <div class="cards" id="results"></div>
  </section>
</main>

<script>
  // ----- 초기 예시 데이터 -----
  const items = [
    {
      id: 1,
      category: "우산",
      color: "검정",
      brand: "",
      locationFound: "2층 복도",
      dateFound: "2025-11-20",
      description: "손잡이에 흰 줄무늬가 있는 자동 우산",
      imagePath: "umbrella1.jpg" // 실제 이미지 파일을 같은 폴더에 두면 썸네일로 보임
    },
    {
      id: 2,
      category: "학용품",
      color: "하늘색",
      brand: "스타벅스",
      locationFound: "도서관 열람실",
      dateFound: "2025-11-18",
      description: "하늘색 스타벅스 펜 파우치, 안에 검정 볼펜 3개",
      imagePath: "pouch1.jpg"
    },
    {
      id: 3,
      category: "카드/지갑",
      color: "밤색",
      brand: "학생증",
      locationFound: "급식실 입구",
      dateFound: "2025-11-19",
      description: "투명 카드 지갑 속에 학생증이 들어 있음",
      imagePath: ""
    }
  ];

  let nextId = items.length ? Math.max(...items.map(i => i.id)) + 1 : 1;

  // DOM 요소
  const registerForm = document.getElementById("register-form");
  const resetBtn = document.getElementById("reset-btn");
  const searchCategory = document.getElementById("searchCategory");
  const keywordInput = document.getElementById("keyword");
  const searchBtn = document.getElementById("searchBtn");
  const clearBtn = document.getElementById("clearBtn");
  const resultsDiv = document.getElementById("results");
  const resultCounter = document.getElementById("resultCounter");

  // 카테고리 옵션 동기화
  function updateCategoryOptions() {
    const categories = Array.from(new Set(items.map(i => i.category))).sort();
    // 기존 옵션 삭제 후 "전체"만 남기기
    while (searchCategory.options.length > 1) {
      searchCategory.remove(1);
    }
    categories.forEach(cat => {
      const opt = document.createElement("option");
      opt.value = cat;
      opt.textContent = cat;
      searchCategory.appendChild(opt);
    });
  }

  // 검색 및 필터링
  function filterItems() {
    const cat = searchCategory.value;
    const keyword = keywordInput.value.trim().toLowerCase();

    let filtered = items.slice();

    if (cat !== "all") {
      filtered = filtered.filter(item => item.category === cat);
    }

    if (keyword) {
      filtered = filtered.filter(item => {
        const combined = [
          item.category,
          item.color,
          item.brand,
          item.locationFound,
          item.dateFound,
          item.description
        ]
          .join(" ")
          .toLowerCase();
        return combined.includes(keyword);
      });
    }

    renderResults(filtered);
  }

  // 결과 렌더링
  function renderResults(list) {
    resultsDiv.innerHTML = "";

    if (!list.length) {
      resultCounter.textContent = "검색 결과가 없습니다.";
      const noDiv = document.createElement("div");
      noDiv.className = "no-result";
      noDiv.textContent = "조건에 맞는 분실물이 없습니다.";
      resultsDiv.appendChild(noDiv);
      return;
    }

    resultCounter.textContent = `검색 결과: ${list.length}개`;

    list.forEach(item => {
      const card = document.createElement("div");
      card.className = "card";

      const thumb = document.createElement("div");
      thumb.className = "card-thumb";

      if (item.imagePath && item.imagePath.trim() !== "") {
        const img = document.createElement("img");
        img.src = item.imagePath;
        img.alt = `분실물 이미지 ${item.id}`;
        thumb.appendChild(img);
      } else {
        thumb.textContent = "이미지 없음";
      }

      const body = document.createElement("div");
      body.className = "card-body";

      const titleLine = document.createElement("div");
      titleLine.className = "title-line";
      titleLine.textContent = `${item.category} · ${item.color || "색상 정보 없음"}`;

      const badges = document.createElement("div");
      const badge1 = document.createElement("span");
      badge1.className = "badge";
      badge1.textContent = item.locationFound || "장소 미상";
      badges.appendChild(badge1);

      if (item.brand) {
        const badge2 = document.createElement("span");
        badge2.className = "badge";
        badge2.textContent = item.brand;
        badges.appendChild(badge2);
      }

      const desc = document.createElement("div");
      desc.textContent = item.description || "(특징 미입력)";

      const meta = document.createElement("div");
      meta.className = "muted";
      meta.textContent = `ID: ${item.id} · 발견 날짜: ${item.dateFound || "미입력"}`;

      body.appendChild(titleLine);
      body.appendChild(badges);
      body.appendChild(desc);
      body.appendChild(meta);

      card.appendChild(thumb);
      card.appendChild(body);
      resultsDiv.appendChild(card);
    });
  }

  // 폼 제출 처리 (분실물 등록)
  registerForm.addEventListener("submit", function (e) {
    e.preventDefault();

    const category = document.getElementById("category").value.trim();
    const color = document.getElementById("color").value.trim();
    const brand = document.getElementById("brand").value.trim();
    const locationFound = document.getElementById("location").value.trim();
    const dateFound = document.getElementById("dateFound").value;
    const description = document.getElementById("description").value.trim();
    const imageName = document.getElementById("imageName").value.trim();

    if (!category) {
      alert("카테고리를 선택해주세요.");
      return;
    }

    const newItem = {
      id: nextId++,
      category,
      color,
      brand,
      locationFound,
      dateFound,
      description,
      imagePath: imageName || ""
    };

    items.push(newItem);
    alert("분실물이 등록되었습니다.");

    registerForm.reset();
    updateCategoryOptions();
    filterItems(); // 현재 검색 조건 기준으로 다시 렌더
  });

  // 폼 초기화 버튼
  resetBtn.addEventListener("click", function () {
    registerForm.reset();
  });

  // 검색 버튼 / 키워드 입력 / 카테고리 변경
  searchBtn.addEventListener("click", filterItems);
  clearBtn.addEventListener("click", function () {
    searchCategory.value = "all";
    keywordInput.value = "";
    filterItems();
  });
  keywordInput.addEventListener("input", filterItems);
  searchCategory.addEventListener("change", filterItems);

  // 초기화
  updateCategoryOptions();
  filterItems();
</script>
</body>
</html>
