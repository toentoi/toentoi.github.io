<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf8" />
	<title>search Test</title>
	<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/latest/css/bootstrap.min.css">
	<script src="//code.jquery.com/jquery.min.js"></script>
	<script src="//maxcdn.bootstrapcdn.com/bootstrap/latest/js/bootstrap.min.js"></script>
	<script language="javascript">
	function blank(){
		if(document.form.search.value==''){

			alert('검색어를 입력해주세요.');

			return false;
		}
		document.form.submit();
	}
	</script>
</head>
<body>

	<form name = "form" form action="box_search.php" method="post" onSubmit="return blank()" >
		<div class="form-group">
			<div class="col-md-2"> <!--열크기조절-->
				<select class="form-control" name="field">
					<option value="itemName">제 품 명</option>
					<option value="itemNum">제품번호</option>
					<option value="eaBarcode" >물량바코드</option>
					<option value="boxBarcode">박스바코드</option>
				</select>
			</div>
			<div class="col-lg-3">
				<div class="input-group">
					<input type="text" class="form-control" name="search" id="search" placeholder="검색어를 입력해 주세요.">
					<!--<input type="submit" value="검색" />-->
					<span class="input-group-btn">
						<button type="submit" class="btn btn-primary glyphicon glyphicon-search" ></button>
					</span>
				</div>
			</div>
		</div>
	</form>

	<?php
		//$connect = mysql_connect("loaclhost","root","qksslfnsl12");
		//$db_con=mysql_select_db("excel",$connect);
	$connect = mysqli_connect("localhost","root","qksslfnsl12","excel");
	if(mysqli_connect_errno()){
		echo "연결실패<br>이유 : " . mysqli_connect_errno();
	}

		//$query = "select * from test where".$searchtype."like'%".$sechterm."%'";
		//$result = mysql_query($connect, $query);
		//$records = mysql_num_rows($result);
		//$fields = mysql_num_fields($result);
		//echo "<p> 관련 제품을 ".$records."개 찾았습니다.</p>";


	$field = $_POST["field"]; 
	$search = $_POST["search"];
	$result = mysqli_query($connect,"SELECT * FROM test where ".$field." like '%".$search."%'");
	//$delete = mysqli_query($connect,"")


	echo "	<br>
	<br>
	<h2> 제품 검색 결과</h2>
	<div class='table-responsive'>
	<table class='table table-striped table-hover'>
	<thead>
		<tr>
		 <th>  번호 </th> 
			<th> 제품 이름 </th> 
			<th> 제품  수량 </th>
			<th> 파레트 </th> 
			<th> 물량바코드 </th>
			<th> 박스바코드 </th>
			<th> 최초 생성일 </th>
			<th> 수 정 </th>
		</tr>
		</thead>";
		
		
		$number=1;
		while($row = mysqli_fetch_array($result)){
			
			echo "<tr>";
			echo "<td>" . $row['itemNum'] . "</td>";
			echo "<td>" . $row['itemName'] . "</td>";
			echo "<td>" . $row['Factor'] . "</td>";
			echo "<td>" . $row['pallet'] . "</td>";
			echo "<td>" . $row['eaBarcode'] . "</td>";
			echo "<td>" . $row['boxBarcode'] . "</td>";
			echo "<td>" . $row['creationDate'] . "</td>";
			echo "<td>" . "<button type='submit' class='btn btn-primary'>수 정</button>" . "</td>";
			echo "</tr>". "</td>";
			$number++;
			
		}
		
		echo "</table>";
		echo "</div>";
		mysqli_close($connect);
		?>
	</form>
</body>
</html>