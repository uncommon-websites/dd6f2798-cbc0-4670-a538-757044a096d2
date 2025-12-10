<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2">Lowest latency with highest reliability</h2>
				<p class="text-xl text-muted font-light">Optimized for production AI workloads</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1">About this benchmark</strong>
				Performance metrics measured across 10,000+ production API calls over 30 days. Latency measured as time-to-first-token (TTFT) for streaming responses. Reliability calculated as successful responses / total requests including automatic failover scenarios. All competitors tested with equivalent model configurations. Learn more in our <a href="#" class="underline">technical documentation</a>.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/30 p-8 font-mono text-xs">
			<!-- Chart Grid -->
			<div class="absolute inset-0 p-8 grid grid-rows-6 grid-cols-1">
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
			</div>
			
			<!-- Y Axis Label -->
			<div class="absolute left-2 top-1/2 -translate-y-1/2 -rotate-90 text-muted origin-center whitespace-nowrap">
				RELIABILITY (%)
			</div>

			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted">
				LATENCY (MS)
			</div>

			<!-- Top Left Legend -->
			<div class="absolute top-4 left-4 flex gap-4 text-[10px] text-muted">
				<span class="bg-gray-200 px-1 rounded text-foreground">Production Benchmark</span>
				<span>30-day average</span>
				<span>10K+ requests</span>
			</div>

			<!-- Data Points -->
			
			<!-- Compile (The Winner) -->
			<div class="absolute top-[8%] left-[12%] flex flex-col items-center group cursor-pointer z-10">
				<div class="flex items-center gap-2 mb-1">
					<span class="text-accent font-bold">COMPILE</span>
				</div>
				<div class="w-3 h-3 bg-accent rounded-full shadow-[0_0_0_4px_rgba(155,81,224,0.2)]"></div>
				<div class="mt-1 text-[10px] text-accent">99.8% / 45ms</div>
			</div>

			<!-- OpenRouter -->
			<div class="absolute top-[35%] left-[25%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-0 group-hover:opacity-100 transition-opacity">
					<span class="font-bold text-[10px]">OPENROUTER</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">96.2% / 78ms</div>
			</div>

			<!-- Martian -->
			<div class="absolute top-[45%] left-[35%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">MARTIAN</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">94.5% / 92ms</div>
			</div>

			<!-- Portkey -->
			<div class="absolute top-[50%] left-[48%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">PORTKEY</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">93.1% / 105ms</div>
			</div>

			<!-- Direct API (baseline) -->
			<div class="absolute top-[60%] right-[25%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">DIRECT API</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">89.3% / 120ms</div>
			</div>

			<!-- Bottom Right Legend -->
			<div class="absolute bottom-4 right-4 flex items-center gap-4 text-[10px]">
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-accent rounded-full"></div>
					<span class="text-accent font-bold">COMPILE</span>
				</div>
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-black rounded-full"></div>
					<span class="text-muted">COMPETITORS</span>
				</div>
			</div>
		</div>
	</div>
</section>
