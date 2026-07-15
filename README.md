// 스크롤 시 헤더 그림자 효과
const header = document.querySelector('.site-header');
window.addEventListener('scroll', () => {
  if (window.scrollY > 8) {
    header.style.boxShadow = '0 1px 0 rgba(16,55,92,0.08)';
  } else {
    header.style.boxShadow = 'none';
  }
});
