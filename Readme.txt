<script type="text/javascript">
	$(document).ready(function () {
		$('#frmLogin').validate({
			rules: {
				"username": {
					required: true,
				},
			},
			messages: {
			  "username": {
				required: "Vui lòng nhập Tên đăng nhập",
			  },
			},
		});
	});	
</script>
