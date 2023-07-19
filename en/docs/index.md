--- 
template: templates/single-column.html 
---

<style>
    @font-face {
    font-family: 'Material Icons';
    font-style: normal;
    font-weight: 400;
    src: url(https://wso2.cachefly.net/wso2/sites/all/fonts/docs/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2) format('woff2');
    }

    .material-icons {
    font-family: 'Material Icons';
    font-weight: normal;
    font-style: normal;
    font-size: 24px;
    line-height: 1;
    letter-spacing: normal;
    text-transform: none;
    display: inline-block;
    white-space: nowrap;
    word-wrap: normal;
    direction: ltr;
    -webkit-font-feature-settings: 'liga';
    -webkit-font-smoothing: antialiased;
    }
</style>

<div>
    <header>
        <h1>Welcome to the WSO2 Open Banking CDS Toolkit Documentation!</h1>
    </header>
    <div class="md-main .md-content" style="float:left; width: 45%;  text-align:justify; max-height:100%; ">
        <p>
        Open Banking CDS Toolkit delivers end-to-end compliance for Australia’s Consumer Data Standard. It increases the speed 
        and reduces the complexity of adopting Consumer Data Right (CDR) compliance for banks. Instead of building an open 
        banking solution from scratch, you can simply deploy WSO2 Open Banking CDS Toolkit to meet all legislative requirements with additional benefits 
        beyond compliance.       
        </p>
        <p>
        The toolkit runs on top of WSO2 Identity Server, WSO2 API Manager, and WSO2 Streaming Integrator. 
        Get a head start with our Quick Start Guide or dive straight into the documentation to understand what we offer.
     </div>
    <div class="md-main .md-content " style="float:right; width: 55%; align:right;  flex-shrink: 0;min-width: 40%; max-height: 100%; max-width:50%; margin-left:10px; margin-top:20px">
        <image src="assets/img/home/accelerator-toolkit-model.png" frameborder="0"></image>
    </div>
    <div>
    	<div class="content">
    		<!-- card -->
    		<div class="card" onclick="location.href='get-started/quick-start-guide';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">timer</i>
    			</div>
    			<div class="card-content" >
    				<p class="title">Quick Start Guide</p>
    				<p class="hint">Set up and try out in your local environment</p>
    			</div>
    		</div>
    		<!-- end card -->
    		<!-- card -->
    		<div class="card" onclick="location.href='learn/consent-management/';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">manage_accounts</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Consent Management</p>
    				<p class="hint">Create, view, revoke, and manage consents</p>
    			</div>
    		</div>
    		<!-- end card -->
    		<!-- card -->
    		<div class="card" onclick="location.href='learn/dynamic-client-registration';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">app_registration</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Dynamic Client Registration</p>
    				<p class="hint">A thorough verification before onboarding</p>
    			</div>
    		</div>
    		<!-- end card -->
    		<!-- card -->
    		<div class="card" onclick="location.href='learn/api-security';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">verified_user</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Secured API Invocation</p>
    				<p class="hint">Comprehensive support of Financial-grade API (FAPI) compliance </p>
    			</div>
    		</div>
    		<!-- end card -->
    	</div>
    	<div class="content">
    		<!-- card -->
    		<div class="card" onclick="location.href='learn/data-publishing/';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">analytics</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Analytics and Data Publishing</p>
    				<p class="hint">Publish and summarize data for reporting</p>
    			</div>
    		</div>
    		<!-- end card -->
    		<!-- card -->
    		<div class="card" onclick="location.href='learn/integration/';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">settings_input_component</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Easily Pluggable</p>
    				<p class="hint">Easy integration with core banking systems</p>
    			</div>
    		</div>
    		<!-- end card -->
    		<!-- 
    		<div class="card" onclick="location.href='develop/develop-toolkit/';">
    			<div class="line"></div>
    			<div class="card-icon">
    				<i class="material-icons md-36">code</i>
    			</div>
    			<div class="card-content">
    				<p class="title">Develop toolkit</p>
    				<p class="hint">Customize features according to your open banking requirements</p>
    			</div>
    		</div>
    		-->
    	</div>
</div>