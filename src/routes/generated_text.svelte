<p>
	<span class="font-bold">Feature:</span> BMW Website Logout Functionality
	<br />
	<br /> <br /><span class="font-bold">Scenario:</span>
	Ensure Logout Button Visibility on Different Pages<br /> Given I am on the BMW website<br />
	When I navigate to "about", "shop", "purchase history" and "dashboard" pages<br />
	Then the logout button should be visible on each page<br /> <br /><span class="font-bold"
		>Scenario:</span
	>
	Confirm Logout Action with Prompt<br /> Given I am logged into the BMW website<br />
	When I click on the logout button<br /> Then a confirmation prompt should appear<br />
	<br /><span class="font-bold">Scenario:</span> Verify Logout Security and Session Termination on
	Two Devices<br />
	Given I am logged into the BMW website on two devices<br /> When I log out from one device<br />
	Then I should be prevented from accessing authenticated pages using the browser's back button on
	that device<br />And I should be prevented from accessing authenticated pages using other devices<br
	/>And the session should be terminated on all devices<br /> <br /><span class="font-bold"
		>Scenario:</span
	>
	Ensure Logout Button Responsiveness on All Screen Sizes<br /> Given I am on the BMW website<br />
	When I access the website on all screen sizes<br /> Then the logout button should adapt and be
	visible on each screen size<br /> <br /><span class="font-bold">Scenario:</span>
	Verify Logout Button Functionality Across Different Browsers<br /> Given I am on the BMW website<br
	/>
	When I access the website from Chrome, Firefox, and Safari<br /> Then the logout button is
	displayed consistently in all browsers<br />
</p>
