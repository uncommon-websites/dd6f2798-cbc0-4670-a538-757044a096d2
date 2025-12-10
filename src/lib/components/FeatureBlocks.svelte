<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: Unified Multi-Model API -->
<FeatureBlock 
	title="One API for 20+ AI models" 
	description="Access GPT-5.1, Claude 4.5, Kimi K2, MiniMax-M2, and 16+ more models through OpenAI and Anthropic-compatible endpoints."
	buttons={[
		{ text: "VIEW ALL MODELS", icon: true },
		{ text: "READ DOCS" }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 font-mono text-xs">
		<div class="flex items-center gap-2 border-b border-border pb-2 mb-4">
			<span class="text-accent">POST</span>
			<span class="text-muted">/v1/chat/completions</span>
		</div>
		<div class="space-y-3 text-[10px]">
			<div class="flex items-start gap-2">
				<span class="text-muted">"model":</span>
				<span class="text-accent">"gpt-5.1"</span>
			</div>
			<div class="flex items-start gap-2">
				<span class="text-muted">"messages":</span>
				<span class="text-foreground">[...]</span>
			</div>
			<div class="mt-4 pt-3 border-t border-border text-muted flex items-center gap-2">
				<span class="w-2 h-2 bg-green-500 rounded-full"></span>
				Response in 45ms
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Automatic Failover & Intelligent Routing -->
<FeatureBlock 
	title="Automatic failover with intelligent routing" 
	description="Built-in redundancy automatically routes requests to healthy providers. Optimize for cost, latency, or quality with intelligent model selection."
	buttons={[
		{ text: "VIEW ARCHITECTURE", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full max-w-md bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center gap-2 text-xs font-mono text-muted mb-2">
			<div class="w-3 h-3 border-2 border-accent rounded-full flex items-center justify-center">
				<div class="w-1.5 h-1.5 bg-accent rounded-full"></div>
			</div>
			Request routing...
		</div>
		<div class="space-y-2 text-[10px] font-mono">
			<div class="flex items-center justify-between p-2 bg-green-50 border border-green-200 rounded">
				<span class="text-green-700">Provider A</span>
				<span class="text-green-600 font-bold">✓ Active</span>
			</div>
			<div class="flex items-center justify-between p-2 bg-red-50 border border-red-200 rounded opacity-50">
				<span class="text-red-700">Provider B</span>
				<span class="text-red-600">✗ Failed</span>
			</div>
			<div class="flex items-center justify-between p-2 bg-green-50 border border-green-200 rounded">
				<span class="text-green-700">Provider C</span>
				<span class="text-green-600 font-bold">✓ Backup</span>
			</div>
		</div>
		<div class="mt-2 flex items-center gap-2 text-[10px] text-accent font-mono">
			<span class="w-2 h-2 bg-accent rounded-full animate-pulse"></span>
			Auto-switched in 12ms
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Deploy Anywhere -->
<FeatureBlock 
	title="Deploy anywhere, run everywhere" 
	description="Choose from hosted cloud, VPC deployment, or on-premises. Complete data sovereignty with air-gapped environments for enterprise compliance."
	buttons={[
		{ text: "EXPLORE DEPLOYMENT", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-3 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>DEPLOYMENT</div>
			<div>ISOLATION</div>
			<div>STATUS</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="flex items-center gap-2">
				<div class="w-3 h-3 rounded-sm bg-accent/20 border border-accent"></div>
				<span class="text-foreground">Hosted Cloud</span>
			</div>
			<div class="text-muted">Shared</div>
			<div class="flex items-center gap-1">
				<div class="w-1.5 h-1.5 bg-green-500 rounded-full"></div>
				<span class="text-green-600">Active</span>
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="flex items-center gap-2">
				<div class="w-3 h-3 rounded-sm bg-blue-400/20 border border-blue-400"></div>
				<span class="text-foreground">VPC</span>
			</div>
			<div class="text-muted">Network</div>
			<div class="flex items-center gap-1">
				<div class="w-1.5 h-1.5 bg-green-500 rounded-full"></div>
				<span class="text-green-600">Active</span>
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="flex items-center gap-2">
				<div class="w-3 h-3 rounded-sm bg-purple-400/20 border border-purple-400"></div>
				<span class="text-foreground">On-Premises</span>
			</div>
			<div class="text-muted">Air-gapped</div>
			<div class="flex items-center gap-1">
				<div class="w-1.5 h-1.5 bg-green-500 rounded-full"></div>
				<span class="text-green-600">Active</span>
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 4: Real-time Monitoring & Analytics -->
<FeatureBlock 
	title="Real-time insights into performance and costs" 
	description="Track API calls, tokens used, total spend, and average latency. Cost attribution across teams with unified governance and quota management."
	buttons={[
		{ text: "VIEW DASHBOARD", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-4 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>METRIC</div>
			<div>CURRENT</div>
			<div>CHANGE</div>
			<div>TREND</div>
		</div>
		<div class="grid grid-cols-4 gap-2 p-3 border-b border-border/50 items-center">
			<div class="text-foreground">API Calls</div>
			<div class="text-foreground font-bold">127.4K</div>
			<div class="text-green-600">+12.3%</div>
			<div class="flex gap-[2px]">
				{#each [3, 5, 4, 6, 8, 7, 9] as h}
					<div class="w-1 bg-green-200" style="height: {h * 2}px"></div>
				{/each}
			</div>
		</div>
		<div class="grid grid-cols-4 gap-2 p-3 border-b border-border/50 items-center">
			<div class="text-foreground">Avg Latency</div>
			<div class="text-foreground font-bold">45ms</div>
			<div class="text-green-600">-8.2%</div>
			<div class="flex gap-[2px]">
				{#each [8, 7, 6, 5, 4, 4, 3] as h}
					<div class="w-1 bg-green-200" style="height: {h * 2}px"></div>
				{/each}
			</div>
		</div>
		<div class="grid grid-cols-4 gap-2 p-3 border-b border-border/50 items-center">
			<div class="text-foreground">Total Spend</div>
			<div class="text-foreground font-bold">$2,847</div>
			<div class="text-green-600">-15.7%</div>
			<div class="flex gap-[2px]">
				{#each [9, 8, 7, 6, 5, 5, 4] as h}
					<div class="w-1 bg-green-200" style="height: {h * 2}px"></div>
				{/each}
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 5: Enterprise Security & Compliance -->
<FeatureBlock 
	title="Enterprise security and compliance" 
	description="SOC 2 Type II certified with zero data retention policy. Enterprise SSO, audit logging, and fine-grained access control. Custom data residency options."
	buttons={[
		{ text: "SECURITY DOCS", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-3">
			<div class="text-[10px] font-mono text-foreground font-bold">Security Status</div>
			<div class="flex items-center gap-1 text-[10px] text-green-600 font-mono">
				<span class="w-2 h-2 bg-green-500 rounded-full"></span>
				All Systems Secure
			</div>
		</div>
		
		<div class="space-y-3 text-[10px] font-mono">
			<div class="flex items-center justify-between p-2 bg-gray-50 rounded">
				<span class="text-foreground">SOC 2 Type II</span>
				<span class="text-green-600 font-bold">✓ Certified</span>
			</div>
			<div class="flex items-center justify-between p-2 bg-gray-50 rounded">
				<span class="text-foreground">Zero Data Retention</span>
				<span class="text-green-600 font-bold">✓ Active</span>
			</div>
			<div class="flex items-center justify-between p-2 bg-gray-50 rounded">
				<span class="text-foreground">End-to-End Encryption</span>
				<span class="text-green-600 font-bold">✓ Enabled</span>
			</div>
			<div class="flex items-center justify-between p-2 bg-gray-50 rounded">
				<span class="text-foreground">Enterprise SSO</span>
				<span class="text-green-600 font-bold">✓ Available</span>
			</div>
		</div>

		<div class="mt-auto pt-3 border-t border-border">
			<div class="flex items-center gap-2 text-[10px] text-muted">
				<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-accent">
					<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path>
				</svg>
				Complete data sovereignty
			</div>
		</div>
	</div>
</FeatureBlock>
