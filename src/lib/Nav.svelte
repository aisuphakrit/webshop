<div class="navbar bg-base-100">
	<div class="navbar-start">
		<div class="dropdown">
			<button type="button" class="btn btn-ghost lg:hidden">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h8m-8 6h16"
					/>
				</svg>
			</button>
			<ul class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
				<li><a href="/">หน้าแรก</a></li>
				<li>
					<a href="/topup">เติมเงิน</a>
					<ul class="p-2">
						<li><a href="/gift">ซองอั่งเปา</a></li>
						<li><a href="/qrcode">คิวอาร์โค้ด</a></li>
					</ul>
				</li>
				<li><a href="/products">สินค้าทิ้งหมด</a></li>
				<li><a href="/register" class="btn btn-sm mb-1 mt-2">สมัครสมาชิก</a></li>
				<li><a href="/login" class="btn btn-sm mt-1">ลงชื่อเข้าใช้</a></li>
			</ul>
		</div>
		<a href="/" class="btn btn-ghost text-xl">Template</a>
	</div>
	<div class="navbar-center hidden lg:flex">
		<ul class="menu menu-horizontal px-1">
			<li><a href="/">หน้าแรก</a></li>
			<li>
				<details>
					<summary>เติมเงิน</summary>
					<ul class="p-2 w-36">
						<li><a href="/gift">ซองอั่งเปา</a></li>
						<li><a href="/qrcode">คิวอาร์โค้ด</a></li>
					</ul>
				</details>
			</li>
			<li><a href="/products">สินค้าทิ้งหมด</a></li>
		</ul>
	</div>
	<div class="navbar-end hidden lg:flex">
		<a href="/register" class="btn mr-1">สมัครสมาชิก</a>
		<a href="/login" class="btn ml-1">ลงชื่อเข้าใช้</a>
	</div>
</div>
