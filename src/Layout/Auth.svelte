<script>
	import { Router, Route } from "svelte-routing";
	
	// import StyleGuide from "../Views/common/guides/StyleGuide.svelte";
	// import DevGuide from "../Views/common/guides/DevGuide.svelte";
	// import Summary from "../Views/Summary.svelte";
	// components for this layout
	// import Header from "../components/Header.svelte";
	// import Footer from "../components/Footer.svelte";
  import Redirect from "../Views/Redirect.svelte";
	import Dashboard from "../Views/Dashboard.svelte";
	// import InternetProfiler from "../Views/common/InternetProfiler.svelte";
	// import ServiceAddress from "../Views/common/ServiceAddress.svelte";
	// import PlanType from "../Views/common/PlanType.svelte";
	// import DeliveryType from "../Views/common/DeliveryType.svelte";
	// import VerificationCode from "../Views/common/VerificationCode.svelte";
	// import PurchaseSummary from "../Views/common/PurchaseSummary.svelte";
	// import Confirm from "../Views/common/Confirm.svelte";
	// import OfferList from "../Views/common/OfferList.svelte";
	// import BranchList from "../Views/common/BranchList.svelte";
	// import Addons from "../Views/common/Addons.svelte";
	// import PaymentType from "../Views/common/PaymentType.svelte";
	// import ServiceAddressInvoice from "../Views/common/ServiceAddressInvoice.svelte";
	// import Documents from "../Views/common/Documents.svelte";
	// import InstallationDate from "../Views/common/InstallationDate.svelte";
	// import VendorInfo from "../Views/common/VendorInfo.svelte";
	// import LeafletList from "../Views/common/LeafletList.svelte";
	// import OrderBox from "../Views/common/OrderBox.svelte";
	// import MySales from "../Views/common/MySales.svelte";
	// import SaleDetail from "../Views/common/SaleDetail.svelte";
	// import BusinessCases from "../Views/common/BusinessCases.svelte";
	// import CreateBusinessCase from "../Views/common/CreateBusinessCase.svelte";
	// import Comment from "../Views/common/Comment.svelte";
</script>

<div>
	<!-- <Header /> -->
	<main>
		<Router url="common">
      <Route path="" component={Redirect} />
			<Route path="dashboard" component={Dashboard} />
			<!-- <Route path="internet-profiler" component={InternetProfiler} />
			<Route path="service-address" component={ServiceAddress} />
			<Route path="style-guide" component={StyleGuide} />
			<Route path="dev-guide" component={DevGuide} />
			<Route path="delivery-type" component={DeliveryType} />
			<Route path="verification-code" component={VerificationCode} />
			<Route path="vendor-info" component={VendorInfo} />
			<Route path="purchase-summary" component={PurchaseSummary} />
			<Route path="plan-type" component={PlanType} />
			<Route path="install-date" component={InstallationDate} />
			<Route path="confirm" component={Confirm} />
			<Route path="offer-list" component={OfferList} />
			<Route path="branch-list" component={BranchList} />
			<Route path="addons" component={Addons} />
			<Route path="payment-type" component={PaymentType} />
			<Route path="service-address-invoice" component={ServiceAddressInvoice} />
			<Route path="documents" component={Documents} />
			<Route path="summary" component={Summary} />
			<Route path="leaflet-list" component={LeafletList} />
			<Route path="order-box" component={OrderBox} />
			<Route path="my-sales" component={MySales} />
			<Route path="sale-detail" component={SaleDetail} />
			<Route path="list-business-cases" component={BusinessCases} />
			<Route path="create-business-case" component={CreateBusinessCase} />
			<Route path="comments" component={Comment} /> -->
		</Router>
	</main>
	<!-- <Footer /> -->
</div>
