<script>
	import '../app.css';
</script>

<svelte:head>
	<!-- Begin Fullstory -->
	<script>
		window['_fs_host'] = 'fullstory.com';
		window['_fs_script'] = 'edge.fullstory.com/s/fs.js';
		window['_fs_org'] = 'o-1D0Q2Y-na1';
		window['_fs_namespace'] = 'FS';
		(function (m, n, e, t, l, o, g, y) {
			if (e in m) {
				if (m.console && m.console.log) {
					m.console.log('FullStory namespace conflict. Please set window["_fs_namespace"].');
				}
				return;
			}
			g = m[e] = function (a, b, s) {
				g.q ? g.q.push([a, b, s]) : g._api(a, b, s);
			};
			g.q = [];
			o = n.createElement(t);
			o.async = 1;
			o.crossOrigin = 'anonymous';
			o.src = 'https://' + _fs_script;
			y = n.getElementsByTagName(t)[0];
			y.parentNode.insertBefore(o, y);
			g.identify = function (i, v, s) {
				g(l, { uid: i }, s);
				if (v) g(l, v, s);
			};
			g.setUserVars = function (v, s) {
				g(l, v, s);
			};
			g.event = function (i, v, s) {
				g('event', { n: i, p: v }, s);
			};
			g.anonymize = function () {
				g.identify(!!0);
			};
			g.shutdown = function () {
				g('rec', !1);
			};
			g.restart = function () {
				g('rec', !0);
			};
			g.log = function (a, b) {
				g('log', [a, b]);
			};
			g.consent = function (a) {
				g('consent', !arguments.length || a);
			};
			g.identifyAccount = function (i, v) {
				o = 'account';
				v = v || {};
				v.acctId = i;
				g(o, v);
			};
			g.clearUserCookie = function () {};
			g.setVars = function (n, p) {
				g('setVars', [n, p]);
			};
			g._w = {};
			y = 'XMLHttpRequest';
			g._w[y] = m[y];
			y = 'fetch';
			g._w[y] = m[y];
			if (m[y])
				m[y] = function () {
					return g._w[y].apply(this, arguments);
				};
			g._v = '1.3.0';
		})(window, document, window['_fs_namespace'], 'script', 'user');
	</script>
	<!-- End Fullstory -->
</svelte:head>

<!-- This example requires Tailwind CSS v2.0+ -->
<header class="bg-white">
	<nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
		<div
			class="w-full py-6 flex items-center justify-between border-b border-slate-600 lg:border-none"
		>
			<div class="flex items-center">
				<a href="/">
					<span class="sr-only">gotoplanb.xyz</span>
					<img
						class="h-10 w-auto"
						src="https://tailwindui.com/img/logos/workflow-mark.svg?color=white"
						alt=""
					/>
				</a>
				<div class="hidden ml-10 space-x-8 lg:block">
					<a href="/" class="text-base font-medium text-slate-600 hover:text-slate-800"> Home </a>

					<a href="/collections" class="text-base font-medium text-slate-600 hover:text-slate-800">
						Collections
					</a>
				</div>
			</div>
			<div class="ml-10 space-x-4">
				<!-- <a href="#" class="inline-block bg-indigo-500 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-opacity-75">Connect</a> -->
			</div>
		</div>
		<div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
			<a href="/" class="text-base font-medium text-slate-600 hover:text-slate-800"> Home </a>

			<a href="/collections" class="text-base font-medium text-slate-600 hover:text-slate-800">
				Collections
			</a>
		</div>
	</nav>
</header>

<slot />
