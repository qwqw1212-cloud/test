//S20210810b3d249e9bb1e8,S2019101540e52034ea8e0,S202301022b2895af4900d - 테스트서버 사이트
// S202112207a3590eef0fe1 슬리피노 / Sleepino
// S2021042276c748218c907 겟비너스
// S202302142a0704f9357df 나비움 | 가벼워지는 나의 매일
// S20200901a942bae14250b 슬롬
// S202011135d3338e327dda 룩트 요거트
// S20210429e1744d8ef448f  힐미
// S20220701ae28ca27ac91b  디어랩스
// S202304275a4d4fe02284a   프리무셀
// S202009292a824c25037d6	라익디스 likethix
// S20210929a609eca26814d	모드라운지 파티룸
// S202406035d30b367f0f0e	커지온
// S202409036cfe271c13545	EVODERM
// S20240903dacb2530c56bb	BKLAB
// S202409032fb33e97f40a8	TRUEV
// S20240903fee1e8ece99ed	유로디에트

const VALID_SITE_CODES = [
	'S20210810b3d249e9bb1e8',
	'S2019101540e52034ea8e0',
	'S202301022b2895af4900d',
	 'S20200901a942bae14250b',
		'S202112207a3590eef0fe1',
		'S2021042276c748218c907',
		'S202302142a0704f9357df',
		'S202011135d3338e327dda',
		'S20210429e1744d8ef448f',
		'S20220701ae28ca27ac91b',
		'S202304275a4d4fe02284a',
		'S202009292a824c25037d6',
		'S20210929a609eca26814d',
		'S202406035d30b367f0f0e',
		'S202409036cfe271c13545',
		'S20240903dacb2530c56bb',
		'S202409032fb33e97f40a8',
		'S20240903fee1e8ece99ed'
];

if (VALID_SITE_CODES.includes(SITE_CODE)) {
	// BrandScope 초기화 및 메서드 사용을 위한 래퍼 함수
	;(
			function(window, document, script, BrandScope, firstScript){
				window.BrandScope = window.BrandScope || {
					init : function(){
						;(
								window.BrandScope.q = window.BrandScope.q || []
						).push(
								['init'].concat(Array.prototype.slice.call(arguments)),
						)
					},
					identify : function(){
						;(
								window.BrandScope.q = window.BrandScope.q || []
						).push(
								['identify'].concat(Array.prototype.slice.call(arguments)),
						)
					},
					track : function(){
						;(
								window.BrandScope.q = window.BrandScope.q || []
						).push(
								['track'].concat(Array.prototype.slice.call(arguments)),
						)
					},
				}

				// BrandScope SDK 스크립트 로드
				BrandScope = window.BrandScope
				// BrandScope 스크립트 동적 로딩
				script = document.createElement('script')
				script.type = 'text/javascript'
				script.async = true
				script.src = (typeof TEST_SERVER !== 'undefined' && TEST_SERVER)
						? '//cdn-brandscope.imtest.me/bs.min.js'
						: '//static.imweb.me/brand-scope/bs.min.js';
				// existing script의 앞에 BrandScope 스크립트 삽입
				firstScript = document.getElementsByTagName('script')[0]
				firstScript.parentNode.insertBefore(script, firstScript)
			}
	)(window, document);
	BrandScope.init()
}
