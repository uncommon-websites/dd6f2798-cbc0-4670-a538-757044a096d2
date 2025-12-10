<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4">Start building</p>
					<h2 class="text-2xl font-medium mb-4">Production-ready AI inference infrastructure</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						Compile delivers high-performance AI workloads through unified multi-model inference with automatic failover and intelligent routing.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							GET BETA ACCESS
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">B</span>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							READ DOCS
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">D</span>
						</button>
					</div>
				</div>
				
				<!-- Abstract Tech Visual -->
				<div class="mt-auto w-full h-48 bg-gradient-to-br from-gray-950 to-gray-900 relative overflow-hidden flex items-center justify-center border border-border">
					{#each Array(100) as _, i}
						<div 
							class="h-full bg-white absolute" 
							style="
								left: {i}%; 
								width: {Math.random() * 2}%; 
								opacity: {Math.random() * 0.1};
							"
						></div>
					{/each}
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-black/80 text-white font-mono text-xs px-3 py-1.5 z-10 border border-white/20 flex items-center gap-2">
							<span class="w-2 h-2 bg-accent rounded-full animate-pulse"></span>
							compile.inference
						</div>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8">Latest updates</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">November 30</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Getting Started with Compile</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Learn how to integrate Compile's unified inference API into your application. This comprehensive guide covers authentication, making your first API call, handling streaming responses, and implementing error handling best practices. Get up and running in under 5 minutes with our OpenAI-compatible endpoints.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Tutorial</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">November 24</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Enterprise Security and Compliance</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Deep dive into Compile's security architecture. Learn about our SOC 2 Type II certification, zero data retention policy, end-to-end encryption, and enterprise SSO capabilities. Discover how our VPC and on-premises deployment options provide complete data sovereignty for regulated industries.
							</p>
							<div class="flex gap-2">
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Security</span>
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Enterprise</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">November 19</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Building Production-Ready AI Agents</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Architecture patterns for building reliable AI agents with Compile. Learn how to leverage automatic failover, implement intelligent model routing based on task complexity, and optimize for cost and latency. Includes real-world examples and code samples.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Guide</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">November 14</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Optimizing LLM Costs: Up to 70% Reduction</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Practical strategies for reducing inference costs without sacrificing quality. Learn about intelligent model routing, caching strategies, and how Compile's unified governance helps track and optimize spending across teams and projects.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Cost Optimization</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
