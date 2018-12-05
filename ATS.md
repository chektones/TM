<h1>ATS</h1>

While making changes to the TradeManager please take account of the fact that some changes might break certain ATS-cases. In this document all the pages and buttons are listed that are used by ATS. When changing a certain element, either change ATS or mention the specific changed element in the ATS-section in the story.

Keep in mind that a change in a certain element does not immediately means it needs to be changed in ATS. Most elements that ATS uses are based on the 'name'-element. For instance, changing the name 'Approve' to something else in Trade Manager/Interest rate fixing/Unverified does not matter. However, deleting the button and create a new button named 'Approve' will cause issues for ATS (assuming you do not rename the 'name'-element). Exceptions are the 'Search'-buttons and the menu-bar: these do not have a name-element, meaning ATS has to rely on the actual name of the menu-item. For instance, changing the menu-item name from 'Trade Manager' to 'Trade manager' will cause issues for ATS. 

<h2>Ribbon</h2>

<ul>
  <li>FAM
    <ul>
      <li>Company and user setup</li>
    </ul>
  </li>
  <li>Administration</li>
  <li>Planning</li>
  <li>Dashboard</li>
  <li>Trade Manager</li>
  <li>My Companies</li>
  <li>Valuation</li>
  <li>Collateral</li>
  <li>Cash</li>
  <li>Risk</li>
  <li>Accounting</li>
  <li>Analyze</li>
  <li>Documents</li>
</ul>

<h2>Pages</h2>

<h3>FAM Company and user setup</h3>
<ul>
  <li>Anonymous
    <ul>
      <li>Any change</li>
    </ul>
  </li>
  <li>CompanyUserSetup (Tab: Company and user setup)
    <ul>
      <li>Edit-button</li>
    </ul>
  </li>
  <li>CompanyUserSetup (Tab: Verification)
    <ul>
      <li>Verify all-button</li>
    </ul>
  </li>
  <li>CompanyUserEdit (Tab: Companies)
    <ul>
      <li>New-button</li>
      <li>Save and submit-button</li>
    </ul>
  </li>
  <li>CompanyUserEdit (Tab: Users)
    <ul>
      <li>New-button</li>
    </ul>
  </li>
  <li>Account_New
    <ul>
      <li>Full name-field</li>
      <li>User name-field</li>
      <li>View type-field</li>
      <li>Language-field</li>
      <li>Save-button</li>
    </ul>
  </li>
  <li>Company_New (Tab: General)
    <ul>
      <li>Legal name-field</li>
      <li>Short name-field</li>
      <li>Address1-field</li>
      <li>Address2-field</li>
      <li>Zip code-field</li>
      <li>City-field</li>
      <li>LEI-field</li>
      <li>Save-button</li>
    </ul>
  </li>
  <li>Company_New (Tab: Deal types)
    <ul>
      <li>Add-button</li>
    </ul>
  </li>
  </li>
  <li>Company_New (Tab: Curve group)
    <ul>
      <li>New button</li>
    </ul>
  </li>
  </li>
  <li>Company_New (Tab: Accounts)
    <ul>
      <li>Add-button</li>
    </ul>
  </li>
  </li>
  <li>Company_New (Tab: Module)
    <ul>
      <li>All checkbox-fields</li>
    </ul>
  </li>
  <li>Snippet_PartyDealTypeConnect
    <ul>
      <li>Deal type-search field</li>
      <li>Search-button</li>
      <li>Deal type-column</li>
      <li>Select-button</li>
    </ul>
  </li>
  <li>AccountCurveGroup_NewEditFAM
    <ul>
      <li>Curve group-field</li>
      <li>Save-button</li>
    </ul>
  </li>
</ul>


<h3>My companies setup</h3>
<ul>
  <li>CompanyAdministration
    <ul>
      <li>Company-column</li>
      <li>Select-button</li>
    </ul>
  </li>
  <li>CompanyManagementStart (Tab: Company management)
    <ul>
      <li>Edit-button</li>
    </ul>
  </li>
  <li>CompanyManagementStart (Tab: Verification/Submitted)
    <ul>
      <li>Verify all-button</li>
    </ul>
  </li>
  <li>CompanyManagementStart (Tab: Verification/Unverified)
    <ul>
      <li>Verify all-button</li>
    </ul>
  </li>
  <li>CompanyManagementEdit (Tab: Security)
    <ul>
      <li>Fixing workflow-field</li>
      <li>Default setting deal workflow-field</li>
      <li>Save and submit-button</li>
    </ul>
  </li>
  <li>CompanyManagementEdit (Tab: Users/General)
    <ul>
      <li>Accept-button (Pending users)</li>
    </ul>
  </li>
  <li>CompanyManagementEdit (Tab: Users/Profile)
    <ul>
      <li>Name-column</li>
      <li>Edit-button</li>
    </ul>
  </li>
  <li>CompanyManagementEdit (Tab: Counterparties)
    <ul>
      <li>Create new counterparty-button</li>
    </ul>
  </li>
  </li>
  <li>AccountProfile_NewEdit (Tab: Curve group)
    <ul>
      <li>User role-field</li>
      <li>New-button</li>
      <li>Add-button (Deal types (Deal))</li>
      <li>New-button (Curve groups)</li>
      <li>Save-button</li>
    </ul>
  </li>
  </li>
  <li>AccountRole_NewEdit
    <ul>
      <li>Account role-field</li>
      <li>Add-button</li>
      <li>Save-button</li>
    </ul>
  </li>
  </li>
  <li>AccountProfile_NewEditModules
    <ul>
      <li>Name-search field</li>
      <li>Search-button</li>
      <li>Select-button</li>
      <li>Select all-button</li>
    </ul>
  </li>
  <li>AccountProfile_NewEditDealTypes
    <ul>
      <li>Select all-button</li>
      <li>Select-button</li>
    </ul>
  </li>
  <li>AccountCurveGroup_enduser_NewEdit 
    <ul>
      <li>Curve group-field</li>
      <li>Save-button</li>
    </ul>
  </li>
  </li>
  <li>AccountParty_AcceptPending 
    <ul>
      <li>Profile-field</li>
      <li>Proceed-button</li>
    </ul>
  </li>
  </li>
  <li>TradingTerms_NewEdit (Tab: Main)
    <ul>
      <li>Legal name-field</li>
      <li>Short name-field</li>
    </ul>
  </li>
  <li>TradingTerms_NewEdit (Tab: Deal types)
    <ul>
      <li>Add-button</li>
    </ul>
  </li>
  <li>TradingTerms_DealType_MultiSelect
    <ul>
      <li>Select all-button</li>
      <li>Select-button</li>
    </ul>
  </li>
</ul>


<h3>Deals overview</h3>
<ul>
  <li>Deals_Overview (Tab: Deal)</li>
  <li>SN_Deals (Tab: Input)
    <ul>
      <li>New-button</li>
    </ul>
  </li>
  <li>SelectDealType
    <ul>
      <li>Company-field</li>
      <li>Deal type-field</li>
    </ul>
  </li>
  <li>CCIRS_New
    <ul>
      <li>Trade date-field</li>
      <li>Effective date-field</li>
      <li>Maturity date-field</li>
      <li>Pay notional-field</li>
      <li>Rec notional-field</li>
      <li>Pay CCY-field</li>
      <li>Rec CCY-field</li>
      <li>Pay float type-field</li>
      <li>Rec float type-field</li>
      <li>Counterparty-field</li>
      <li>Save and submit-button</li>
    </ul>
  </li>
    <li>CCIRS_New (Tabs: Pay/Receive legs)
    <ul>
      <li>Payments in-field</li>
      <li>Accrual method-field</li>
      <li>Business day convention-field</li>
      <li>Payment frequency-field</li>
      <li>Reset frequency-field</li>
      <li>Reset type-field</li>
      <li>Initial floating rate-field</li>
      <li>Floating rate spread-field</li>
      <li>Compounding-field</li>
      <li>Floating rate benchmark-field</li>
      <li>Date of first reset date-field</li>
    </ul>
  </li>
  <li>CCIRS_New (Tabs: Valuation)
    <ul>
      <li>Pay discount curve-field</li>
      <li>Pay forward curve-field</li>
      <li>Receive discount curve-field</li>
      <li>Receive forward curve-field</li>
    </ul>
  </li>
  <li>CCIRS_New (Tabs: Schedule)
    <ul>
      <li>Generate schedule-button</li>
    </ul>
  </li>
  <li>CCIRS_New (Tab: Fees)</li>
  <li>CCIRS_New (Tab: Cashflow overview)
    <ul>
      <li>Calculate cashflows-button</li>
    </ul>
  </li>
  <li>CCIRS_New (Tab: Other details)
    <ul>
      <li>Fixing definition-field</li>
      <li>Fallback-definition-field</li>
    </ul>
  </li>
  <li>SN_Deals (Tab: Submitted)
    <ul>
      <li>Verify deal-button</li>
    </ul>
  </li>
  </li>
  <li>SN_Deals (Tab: Unverified)
    <ul>
      <li>Verify deal-button</li>
    </ul>
  </li>
</ul>



<h3>Fixings workflow</h3>
<ul>
  <li>Deals_Overview (Tab: Interest rate fixing/Historical)
    <ul>
      <li>Company-search field</li>
      <li>Other ref-search field</li>
      <li>Search-button</li>
      <li>Company-column</li>
      <li>Actualize-button</li>
    </ul>
  </li>
  <li>Deals_Overview (Tab: FX fixing/Historical)
    <ul>
      <li>Other ref-column</li>
      <li>Other ref-search field</li>
      <li>Search-button</li>
      <li>Actualize-button</li>
    </ul>
  </li>
  <li>Deals_Overview (Tab: FX fixing/Maintenance)</li>
  <li>Deals_Overview (Tab: Interest rate fixing/Maintenance)</li>
  <li>Deals_Overview (Tab: Interest rate fixing/Submitted)
    <ul>
      <li>Approve-button</li>
      <li>Select all-button</li>
    </ul>
  </li>
    <li>Deals_Overview (Tab: Interest rate fixing/Unverified)
    <ul>
      <li>Approve-button</li>
      <li>Select all-button</li>
    </ul>
  </li>
    <li>Deals_Overview (Tab: FX fixing/Submitted)
    <ul>
      <li>Approve-button</li>
      <li>Select all-button</li>
    </ul>
  </li>
    <li>Deals_Overview (Tab: FX fixing/Unverified)
    <ul>
      <li>Approve-button</li>
      <li>Select all-button</li>
    </ul>
  </li>
  <li>ActualizeCashflow_Rate
    <ul>
      <li>Interest rate fixing-field</li>
      <li>Actualize cashflow-button</li>
    </ul>
  </li>
    <li>ActualizeCashflow_NDFixingRate
    <ul>
      <li>FX fixing rate fixing-field</li>
      <li>Actualize cashflow-button</li>
    </ul>
  </li>
  </ul>
    
